# Server Metrics 2026-03-13 03:35:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 77820.5 (21h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2145797
telemt_connections_bad_total 28005
telemt_handshake_timeouts_total 22903
telemt_upstream_connect_attempt_total 15429
telemt_upstream_connect_success_total 15342
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 15429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 1296
telemt_me_reconnect_attempts_total 20318
telemt_me_reconnect_success_total 11455
telemt_me_reader_eof_total 12372
telemt_me_idle_close_by_peer_total 12371
telemt_me_route_drop_no_conn_total 822584
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1973191
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8802
telemt_desync_full_logged_total 2288
telemt_desync_suppressed_total 6514
telemt_desync_frames_bucket_total{bucket="1_2"} 2316
telemt_desync_frames_bucket_total{bucket="3_10"} 3174
telemt_desync_frames_bucket_total{bucket="gt_10"} 3312
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11891
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 11442
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 436
telemt_user_connections_total{user="hello"} 1972637
telemt_user_connections_current{user="hello"} 853
telemt_user_octets_from_client{user="hello"} 28664905008 (26.70 GB)
telemt_user_octets_to_client{user="hello"} 680857526756 (634.10 GB)
telemt_user_unique_ips_current{user="hello"} 288
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 107441.0 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 873932
telemt_connections_bad_total 11846
telemt_handshake_timeouts_total 38205
telemt_upstream_connect_attempt_total 27398
telemt_upstream_connect_success_total 27369
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 27398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13098
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3462
telemt_me_reconnect_attempts_total 20477
telemt_me_reconnect_success_total 20365
telemt_me_reader_eof_total 21707
telemt_me_idle_close_by_peer_total 21707
telemt_me_route_drop_no_conn_total 279749
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 788180
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3127
telemt_desync_full_logged_total 982
telemt_desync_suppressed_total 2145
telemt_desync_frames_bucket_total{bucket="1_2"} 1266
telemt_desync_frames_bucket_total{bucket="3_10"} 1014
telemt_desync_frames_bucket_total{bucket="gt_10"} 847
telemt_pool_swap_total 110
telemt_me_writer_removed_unexpected_total 20564
telemt_me_writer_restored_same_endpoint_total 20356
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 790083
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 12601523332 (11.74 GB)
telemt_user_octets_to_client{user="hello"} 304127825247 (283.24 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 96
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 107441.0 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1806964
telemt_connections_bad_total 11875
telemt_handshake_timeouts_total 119966
telemt_upstream_connect_attempt_total 25075
telemt_upstream_connect_success_total 25065
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 25075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 1621
telemt_me_reconnect_attempts_total 20620
telemt_me_reconnect_success_total 19354
telemt_me_reader_eof_total 20506
telemt_me_idle_close_by_peer_total 20505
telemt_me_route_drop_no_conn_total 586696
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1424785
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5082
telemt_desync_full_logged_total 1550
telemt_desync_suppressed_total 3532
telemt_desync_frames_bucket_total{bucket="1_2"} 811
telemt_desync_frames_bucket_total{bucket="3_10"} 1837
telemt_desync_frames_bucket_total{bucket="gt_10"} 2434
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 19535
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 19313
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 1424379
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 24752003964 (23.05 GB)
telemt_user_octets_to_client{user="hello"} 510576283797 (475.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 107441.3 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1125011
telemt_connections_bad_total 13149
telemt_handshake_timeouts_total 74209
telemt_upstream_connect_attempt_total 37367
telemt_upstream_connect_success_total 35086
telemt_upstream_connect_fail_total 2144
telemt_upstream_connect_attempts_per_request{bucket="1"} 37093
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13303
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2143
telemt_me_keepalive_timeout_total 11375
telemt_me_reconnect_attempts_total 32789
telemt_me_reconnect_success_total 23859
telemt_me_reader_eof_total 25762
telemt_me_idle_close_by_peer_total 25755
telemt_me_route_drop_no_conn_total 399304
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 965726
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1906
telemt_desync_full_logged_total 632
telemt_desync_suppressed_total 1274
telemt_desync_frames_bucket_total{bucket="1_2"} 529
telemt_desync_frames_bucket_total{bucket="3_10"} 746
telemt_desync_frames_bucket_total{bucket="gt_10"} 631
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 24294
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 23835
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 435
telemt_user_connections_total{user="hello"} 970896
telemt_user_connections_current{user="hello"} 321
telemt_user_octets_from_client{user="hello"} 14840155489 (13.82 GB)
telemt_user_octets_to_client{user="hello"} 383108881674 (356.80 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 53
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 107441.2 (29h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1246015
telemt_connections_bad_total 12862
telemt_handshake_timeouts_total 9883
telemt_upstream_connect_attempt_total 33799
telemt_upstream_connect_success_total 33386
telemt_upstream_connect_fail_total 413
telemt_upstream_connect_attempts_per_request{bucket="1"} 33799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16075
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 413
telemt_me_keepalive_timeout_total 1909
telemt_me_reconnect_attempts_total 41760
telemt_me_reconnect_success_total 28030
telemt_me_reader_eof_total 29491
telemt_me_idle_close_by_peer_total 29491
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 464314
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1152273
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 42
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 4266
telemt_desync_full_logged_total 1523
telemt_desync_suppressed_total 2743
telemt_desync_frames_bucket_total{bucket="1_2"} 1290
telemt_desync_frames_bucket_total{bucket="3_10"} 1399
telemt_desync_frames_bucket_total{bucket="gt_10"} 1577
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 28780
telemt_me_refill_failed_total 425
telemt_me_writer_restored_same_endpoint_total 27980
telemt_me_writer_restored_fallback_total 50
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 750
telemt_user_connections_total{user="hello"} 1152128
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 14204786288 (13.23 GB)
telemt_user_octets_to_client{user="hello"} 396995982316 (369.73 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 43
```