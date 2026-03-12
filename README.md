# Server Metrics 2026-03-12 19:41:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 49358.0 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1732740
telemt_connections_bad_total 20544
telemt_handshake_timeouts_total 17646
telemt_upstream_connect_attempt_total 9674
telemt_upstream_connect_success_total 9619
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 9674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4571
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_keepalive_timeout_total 574
telemt_me_reconnect_attempts_total 15975
telemt_me_reconnect_success_total 7128
telemt_me_reader_eof_total 7717
telemt_me_idle_close_by_peer_total 7716
telemt_me_route_drop_no_conn_total 681969
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1618455
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8114
telemt_desync_full_logged_total 2085
telemt_desync_suppressed_total 6029
telemt_desync_frames_bucket_total{bucket="1_2"} 2116
telemt_desync_frames_bucket_total{bucket="3_10"} 2926
telemt_desync_frames_bucket_total{bucket="gt_10"} 3072
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 7508
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 7115
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 380
telemt_user_connections_total{user="hello"} 1617946
telemt_user_connections_current{user="hello"} 1299
telemt_user_octets_from_client{user="hello"} 25125961252 (23.40 GB)
telemt_user_octets_to_client{user="hello"} 555649068612 (517.49 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 78978.3 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 736965
telemt_connections_bad_total 10368
telemt_handshake_timeouts_total 29981
telemt_upstream_connect_attempt_total 20050
telemt_upstream_connect_success_total 20021
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 20050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 84
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_keepalive_timeout_total 3374
telemt_me_reconnect_attempts_total 14511
telemt_me_reconnect_success_total 14424
telemt_me_reader_eof_total 15334
telemt_me_idle_close_by_peer_total 15334
telemt_me_route_drop_no_conn_total 236228
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 664154
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2864
telemt_desync_full_logged_total 879
telemt_desync_suppressed_total 1985
telemt_desync_frames_bucket_total{bucket="1_2"} 1120
telemt_desync_frames_bucket_total{bucket="3_10"} 941
telemt_desync_frames_bucket_total{bucket="gt_10"} 803
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 14574
telemt_me_writer_restored_same_endpoint_total 14415
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 666031
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 11301036668 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 250553635415 (233.35 GB)
telemt_user_msgs_from_client{user="hello"} 6476
telemt_user_msgs_to_client{user="hello"} 18854
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 78978.3 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1522937
telemt_connections_bad_total 7278
telemt_handshake_timeouts_total 103922
telemt_upstream_connect_attempt_total 18625
telemt_upstream_connect_success_total 18620
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 18625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8532
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1187
telemt_me_reconnect_attempts_total 15553
telemt_me_reconnect_success_total 14307
telemt_me_reader_eof_total 15094
telemt_me_idle_close_by_peer_total 15093
telemt_me_route_drop_no_conn_total 501484
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1168627
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4785
telemt_desync_full_logged_total 1474
telemt_desync_suppressed_total 3311
telemt_desync_frames_bucket_total{bucket="1_2"} 755
telemt_desync_frames_bucket_total{bucket="3_10"} 1736
telemt_desync_frames_bucket_total{bucket="gt_10"} 2294
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 14439
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 14266
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 1168477
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 18211195808 (16.96 GB)
telemt_user_octets_to_client{user="hello"} 433223664389 (403.47 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 234
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 78978.9 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 930946
telemt_connections_bad_total 12967
telemt_handshake_timeouts_total 68246
telemt_upstream_connect_attempt_total 20256
telemt_upstream_connect_success_total 20175
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 20256
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11320
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8842
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 1645
telemt_me_reconnect_attempts_total 23955
telemt_me_reconnect_success_total 16230
telemt_me_reader_eof_total 17335
telemt_me_idle_close_by_peer_total 17335
telemt_me_route_drop_no_conn_total 330633
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 806714
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1748
telemt_desync_full_logged_total 585
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 490
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 581
telemt_pool_swap_total 64
telemt_me_writer_removed_unexpected_total 16603
telemt_me_refill_failed_total 239
telemt_me_writer_restored_same_endpoint_total 16209
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 373
telemt_user_connections_total{user="hello"} 806071
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 12498491468 (11.64 GB)
telemt_user_octets_to_client{user="hello"} 329980850356 (307.32 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 78978.6 (21h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1046986
telemt_connections_bad_total 12335
telemt_handshake_timeouts_total 8629
telemt_upstream_connect_attempt_total 24481
telemt_upstream_connect_success_total 24184
telemt_upstream_connect_fail_total 297
telemt_upstream_connect_attempts_per_request{bucket="1"} 24481
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 123
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 297
telemt_me_keepalive_timeout_total 1395
telemt_me_reconnect_attempts_total 31257
telemt_me_reconnect_success_total 20221
telemt_me_reader_eof_total 21248
telemt_me_idle_close_by_peer_total 21248
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 391712
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 960189
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 3598
telemt_desync_full_logged_total 1258
telemt_desync_suppressed_total 2340
telemt_desync_frames_bucket_total{bucket="1_2"} 1026
telemt_desync_frames_bucket_total{bucket="3_10"} 1197
telemt_desync_frames_bucket_total{bucket="gt_10"} 1375
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 20794
telemt_me_refill_failed_total 342
telemt_me_writer_restored_same_endpoint_total 20177
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 573
telemt_user_connections_total{user="hello"} 960059
telemt_user_connections_current{user="hello"} 637
telemt_user_octets_from_client{user="hello"} 11880714440 (11.06 GB)
telemt_user_octets_to_client{user="hello"} 327716736484 (305.21 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 81
```