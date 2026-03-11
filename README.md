# Server Metrics 2026-03-11 19:57:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 106243.6 (29h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2697653
telemt_connections_bad_total 50363
telemt_handshake_timeouts_total 60377
telemt_upstream_connect_attempt_total 22451
telemt_upstream_connect_success_total 22439
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 22451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11323
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11005
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5398
telemt_me_reconnect_attempts_total 34966
telemt_me_reconnect_success_total 17073
telemt_me_reader_eof_total 18433
telemt_me_idle_close_by_peer_total 18433
telemt_me_route_drop_no_conn_total 1018235
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2461983
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12479
telemt_desync_full_logged_total 3462
telemt_desync_suppressed_total 9017
telemt_desync_frames_bucket_total{bucket="1_2"} 3069
telemt_desync_frames_bucket_total{bucket="3_10"} 4814
telemt_desync_frames_bucket_total{bucket="gt_10"} 4596
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17826
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17067
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 753
telemt_user_connections_total{user="hello"} 2460334
telemt_user_connections_current{user="hello"} 1058
telemt_user_octets_from_client{user="hello"} 36623384800 (34.11 GB)
telemt_user_octets_to_client{user="hello"} 700425913820 (652.32 GB)
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 106299.4 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 999220
telemt_connections_bad_total 16494
telemt_handshake_timeouts_total 90203
telemt_upstream_connect_attempt_total 32675
telemt_upstream_connect_success_total 29702
telemt_upstream_connect_fail_total 2972
telemt_upstream_connect_attempts_per_request{bucket="1"} 32674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13364
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2077
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2972
telemt_me_keepalive_timeout_total 2867
telemt_me_reconnect_attempts_total 23511
telemt_me_reconnect_success_total 21391
telemt_me_reader_eof_total 22646
telemt_me_idle_close_by_peer_total 22643
telemt_me_route_drop_no_conn_total 377610
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 833764
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3321
telemt_desync_full_logged_total 1076
telemt_desync_suppressed_total 2245
telemt_desync_frames_bucket_total{bucket="1_2"} 1061
telemt_desync_frames_bucket_total{bucket="3_10"} 1180
telemt_desync_frames_bucket_total{bucket="gt_10"} 1080
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 21703
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21368
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 836215
telemt_user_connections_current{user="hello"} 304
telemt_user_octets_from_client{user="hello"} 10062529194 (9.37 GB)
telemt_user_octets_to_client{user="hello"} 242995341076 (226.31 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 106299.3 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1727298
telemt_connections_bad_total 10827
telemt_handshake_timeouts_total 134413
telemt_upstream_connect_attempt_total 27224
telemt_upstream_connect_success_total 26883
telemt_upstream_connect_fail_total 340
telemt_upstream_connect_attempts_per_request{bucket="1"} 27223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 340
telemt_me_keepalive_timeout_total 2011
telemt_me_reconnect_attempts_total 54137
telemt_me_reconnect_success_total 20418
telemt_me_reader_eof_total 22330
telemt_me_idle_close_by_peer_total 22330
telemt_me_route_drop_no_conn_total 628790
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1517317
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4131
telemt_desync_full_logged_total 1219
telemt_desync_suppressed_total 2912
telemt_desync_frames_bucket_total{bucket="1_2"} 967
telemt_desync_frames_bucket_total{bucket="3_10"} 1570
telemt_desync_frames_bucket_total{bucket="gt_10"} 1594
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 21752
telemt_me_refill_failed_total 1048
telemt_me_writer_restored_same_endpoint_total 20406
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1334
telemt_user_connections_total{user="hello"} 1516959
telemt_user_connections_current{user="hello"} 619
telemt_user_octets_from_client{user="hello"} 19565328045 (18.22 GB)
telemt_user_octets_to_client{user="hello"} 465182644981 (433.24 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 185
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 106300.0 (29h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1233382
telemt_connections_bad_total 78219
telemt_handshake_timeouts_total 111028
telemt_upstream_connect_attempt_total 28671
telemt_upstream_connect_success_total 28671
telemt_upstream_connect_attempts_per_request{bucket="1"} 28671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1473
telemt_me_reconnect_attempts_total 27947
telemt_me_reconnect_success_total 23332
telemt_me_reader_eof_total 24770
telemt_me_idle_close_by_peer_total 24769
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 414115
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1008753
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2170
telemt_desync_full_logged_total 812
telemt_desync_suppressed_total 1358
telemt_desync_frames_bucket_total{bucket="1_2"} 774
telemt_desync_frames_bucket_total{bucket="3_10"} 731
telemt_desync_frames_bucket_total{bucket="gt_10"} 665
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23719
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23299
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 387
telemt_user_connections_total{user="hello"} 1007879
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 11977636100 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 308762652784 (287.56 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 10975.8 (3h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171615
telemt_connections_bad_total 3811
telemt_handshake_timeouts_total 1794
telemt_upstream_connect_attempt_total 3142
telemt_upstream_connect_success_total 3141
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 3142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 2541
telemt_me_reconnect_success_total 2515
telemt_me_reader_eof_total 2587
telemt_me_idle_close_by_peer_total 2587
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 57318
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151285
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 346
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 232
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2542
telemt_me_writer_restored_same_endpoint_total 2490
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 151255
telemt_user_connections_current{user="hello"} 493
telemt_user_octets_from_client{user="hello"} 9375218096 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 50571921960 (47.10 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 64
```