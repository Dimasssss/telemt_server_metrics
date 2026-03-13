# Server Metrics 2026-03-13 08:26:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 95274.2 (26h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2660967
telemt_connections_bad_total 36273
telemt_handshake_timeouts_total 29531
telemt_upstream_connect_attempt_total 18492
telemt_upstream_connect_success_total 18391
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1367
telemt_me_reconnect_attempts_total 22546
telemt_me_reconnect_success_total 13673
telemt_me_reader_eof_total 14737
telemt_me_idle_close_by_peer_total 14736
telemt_me_route_drop_no_conn_total 991545
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2434955
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10982
telemt_desync_full_logged_total 2837
telemt_desync_suppressed_total 8145
telemt_desync_frames_bucket_total{bucket="1_2"} 2821
telemt_desync_frames_bucket_total{bucket="3_10"} 4111
telemt_desync_frames_bucket_total{bucket="gt_10"} 4050
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 14141
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 13660
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 468
telemt_user_connections_total{user="hello"} 2434552
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 34409515296 (32.05 GB)
telemt_user_octets_to_client{user="hello"} 809633794832 (754.03 GB)
telemt_user_unique_ips_current{user="hello"} 435
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 124894.7 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1086147
telemt_connections_bad_total 13606
telemt_handshake_timeouts_total 88446
telemt_upstream_connect_attempt_total 31161
telemt_upstream_connect_success_total 31130
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 31161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 3633
telemt_me_reconnect_attempts_total 23414
telemt_me_reconnect_success_total 23293
telemt_me_reader_eof_total 24825
telemt_me_idle_close_by_peer_total 24825
telemt_me_route_drop_no_conn_total 334626
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 943495
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4184
telemt_desync_full_logged_total 1276
telemt_desync_suppressed_total 2908
telemt_desync_frames_bucket_total{bucket="1_2"} 1543
telemt_desync_frames_bucket_total{bucket="3_10"} 1369
telemt_desync_frames_bucket_total{bucket="gt_10"} 1272
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 23522
telemt_me_writer_restored_same_endpoint_total 23284
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 945420
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 14508412328 (13.51 GB)
telemt_user_octets_to_client{user="hello"} 351751024163 (327.59 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 124894.8 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2124950
telemt_connections_bad_total 23673
telemt_handshake_timeouts_total 142648
telemt_upstream_connect_attempt_total 28686
telemt_upstream_connect_success_total 28676
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 28686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13528
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1743
telemt_me_reconnect_attempts_total 23406
telemt_me_reconnect_success_total 22125
telemt_me_reader_eof_total 23435
telemt_me_idle_close_by_peer_total 23434
telemt_me_route_drop_no_conn_total 687321
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1691548
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5679
telemt_desync_full_logged_total 1799
telemt_desync_suppressed_total 3880
telemt_desync_frames_bucket_total{bucket="1_2"} 931
telemt_desync_frames_bucket_total{bucket="3_10"} 2075
telemt_desync_frames_bucket_total{bucket="gt_10"} 2673
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 22341
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 22084
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 1691010
telemt_user_connections_current{user="hello"} 903
telemt_user_octets_from_client{user="hello"} 28104220384 (26.17 GB)
telemt_user_octets_to_client{user="hello"} 613658668957 (571.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 285
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 124895.1 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1352336
telemt_connections_bad_total 14217
telemt_handshake_timeouts_total 83428
telemt_upstream_connect_attempt_total 41723
telemt_upstream_connect_success_total 39422
telemt_upstream_connect_fail_total 2164
telemt_upstream_connect_attempts_per_request{bucket="1"} 41449
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2163
telemt_me_keepalive_timeout_total 11448
telemt_me_reconnect_attempts_total 36300
telemt_me_reconnect_success_total 27360
telemt_me_reader_eof_total 29465
telemt_me_idle_close_by_peer_total 29458
telemt_me_route_drop_no_conn_total 473353
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1123681
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2180
telemt_desync_full_logged_total 711
telemt_desync_suppressed_total 1469
telemt_desync_frames_bucket_total{bucket="1_2"} 600
telemt_desync_frames_bucket_total{bucket="3_10"} 837
telemt_desync_frames_bucket_total{bucket="gt_10"} 743
telemt_pool_swap_total 107
telemt_me_writer_removed_unexpected_total 27831
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 27336
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 1128435
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 17059288717 (15.89 GB)
telemt_user_octets_to_client{user="hello"} 451380960718 (420.38 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 90
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 124894.9 (34h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1487889
telemt_connections_bad_total 29791
telemt_handshake_timeouts_total 12365
telemt_upstream_connect_attempt_total 39378
telemt_upstream_connect_success_total 38901
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 39378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18944
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_keepalive_timeout_total 2140
telemt_me_reconnect_attempts_total 46443
telemt_me_reconnect_success_total 32701
telemt_me_reader_eof_total 34307
telemt_me_idle_close_by_peer_total 34307
telemt_me_seq_mismatch_total 46
telemt_me_route_drop_no_conn_total 545386
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1364896
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 50
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4798
telemt_desync_full_logged_total 1716
telemt_desync_suppressed_total 3082
telemt_desync_frames_bucket_total{bucket="1_2"} 1461
telemt_desync_frames_bucket_total{bucket="3_10"} 1553
telemt_desync_frames_bucket_total{bucket="gt_10"} 1784
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 33489
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 32643
telemt_me_writer_restored_fallback_total 58
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 788
telemt_user_connections_total{user="hello"} 1364701
telemt_user_connections_current{user="hello"} 830
telemt_user_octets_from_client{user="hello"} 17413565316 (16.22 GB)
telemt_user_octets_to_client{user="hello"} 473588898268 (441.06 GB)
telemt_user_unique_ips_current{user="hello"} 221
telemt_user_unique_ips_recent_window{user="hello"} 120
```