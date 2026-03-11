# Server Metrics 2026-03-11 05:35:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 54526.0 (15h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1063928
telemt_connections_bad_total 12320
telemt_handshake_timeouts_total 37313
telemt_upstream_connect_attempt_total 11627
telemt_upstream_connect_success_total 11618
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 11627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 547
telemt_me_reconnect_attempts_total 20523
telemt_me_reconnect_success_total 8844
telemt_me_reader_eof_total 9627
telemt_me_idle_close_by_peer_total 9627
telemt_me_route_drop_no_conn_total 392611
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 954561
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4370
telemt_desync_full_logged_total 1239
telemt_desync_suppressed_total 3131
telemt_desync_frames_bucket_total{bucket="1_2"} 1215
telemt_desync_frames_bucket_total{bucket="3_10"} 1648
telemt_desync_frames_bucket_total{bucket="gt_10"} 1507
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 9290
telemt_me_refill_failed_total 363
telemt_me_writer_restored_same_endpoint_total 8838
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 954265
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 12857195216 (11.97 GB)
telemt_user_octets_to_client{user="hello"} 278281677288 (259.17 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 138
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54582.7 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410880
telemt_connections_bad_total 2853
telemt_handshake_timeouts_total 19547
telemt_upstream_connect_attempt_total 20176
telemt_upstream_connect_success_total 17268
telemt_upstream_connect_fail_total 2907
telemt_upstream_connect_attempts_per_request{bucket="1"} 20175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7304
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2907
telemt_me_keepalive_timeout_total 1792
telemt_me_reconnect_attempts_total 12403
telemt_me_reconnect_success_total 11581
telemt_me_reader_eof_total 12237
telemt_me_idle_close_by_peer_total 12235
telemt_me_route_drop_no_conn_total 192481
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353345
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1874
telemt_desync_full_logged_total 562
telemt_desync_suppressed_total 1312
telemt_desync_frames_bucket_total{bucket="1_2"} 591
telemt_desync_frames_bucket_total{bucket="3_10"} 672
telemt_desync_frames_bucket_total{bucket="gt_10"} 611
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11716
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 11560
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 355615
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 3562868330 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 87304133080 (81.31 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 54582.7 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 702562
telemt_connections_bad_total 5982
telemt_handshake_timeouts_total 38424
telemt_upstream_connect_attempt_total 14747
telemt_upstream_connect_success_total 14552
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 14747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 573
telemt_me_reconnect_attempts_total 21811
telemt_me_reconnect_success_total 10739
telemt_me_reader_eof_total 11600
telemt_me_idle_close_by_peer_total 11600
telemt_me_route_drop_no_conn_total 236761
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627339
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1737
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1221
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 612
telemt_desync_frames_bucket_total{bucket="gt_10"} 738
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 11226
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 10728
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 628196
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 7612755253 (7.09 GB)
telemt_user_octets_to_client{user="hello"} 186949265569 (174.11 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 54582.9 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 535196
telemt_connections_bad_total 51275
telemt_handshake_timeouts_total 55736
telemt_upstream_connect_attempt_total 15696
telemt_upstream_connect_success_total 15696
telemt_upstream_connect_attempts_per_request{bucket="1"} 15696
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 496
telemt_me_reconnect_attempts_total 14001
telemt_me_reconnect_success_total 12958
telemt_me_reader_eof_total 13743
telemt_me_idle_close_by_peer_total 13743
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 157751
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413535
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 884
telemt_desync_full_logged_total 365
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13106
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 12936
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 413174
telemt_user_connections_current{user="hello"} 408
telemt_user_octets_from_client{user="hello"} 5019912212 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 113597093068 (105.80 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 64
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 54582.5 (15h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558674
telemt_connections_bad_total 5956
telemt_handshake_timeouts_total 3775
telemt_upstream_connect_attempt_total 15643
telemt_upstream_connect_success_total 15578
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 15643
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 564
telemt_me_reconnect_attempts_total 16580
telemt_me_reconnect_success_total 12797
telemt_me_reader_eof_total 13500
telemt_me_idle_close_by_peer_total 13500
telemt_me_route_drop_no_conn_total 182285
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 510116
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2506
telemt_desync_full_logged_total 969
telemt_desync_suppressed_total 1537
telemt_desync_frames_bucket_total{bucket="1_2"} 907
telemt_desync_frames_bucket_total{bucket="3_10"} 1067
telemt_desync_frames_bucket_total{bucket="gt_10"} 532
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 13077
telemt_me_refill_failed_total 116
telemt_me_writer_restored_same_endpoint_total 12797
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 509737
telemt_user_connections_current{user="hello"} 417
telemt_user_octets_from_client{user="hello"} 9108072740 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 179024728068 (166.73 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 71
```