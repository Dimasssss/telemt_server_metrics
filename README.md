# Server Metrics 2026-03-11 20:48:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 109304.2 (30h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2770752
telemt_connections_bad_total 59371
telemt_handshake_timeouts_total 62251
telemt_upstream_connect_attempt_total 23245
telemt_upstream_connect_success_total 23233
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 23245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11729
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 5418
telemt_me_reconnect_attempts_total 35583
telemt_me_reconnect_success_total 17689
telemt_me_reader_eof_total 19080
telemt_me_idle_close_by_peer_total 19080
telemt_me_route_drop_no_conn_total 1041545
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2517503
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12692
telemt_desync_full_logged_total 3527
telemt_desync_suppressed_total 9165
telemt_desync_frames_bucket_total{bucket="1_2"} 3130
telemt_desync_frames_bucket_total{bucket="3_10"} 4881
telemt_desync_frames_bucket_total{bucket="gt_10"} 4681
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18452
telemt_me_refill_failed_total 555
telemt_me_writer_restored_same_endpoint_total 17683
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 920
telemt_me_writer_removed_unexpected_minus_restored_total 763
telemt_user_connections_total{user="hello"} 2515845
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 38194931568 (35.57 GB)
telemt_user_octets_to_client{user="hello"} 725994729556 (676.14 GB)
telemt_user_unique_ips_current{user="hello"} 260
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 109361.0 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1014800
telemt_connections_bad_total 17046
telemt_handshake_timeouts_total 90422
telemt_upstream_connect_attempt_total 33393
telemt_upstream_connect_success_total 30418
telemt_upstream_connect_fail_total 2975
telemt_upstream_connect_attempts_per_request{bucket="1"} 33393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 209
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2975
telemt_me_keepalive_timeout_total 2890
telemt_me_reconnect_attempts_total 24090
telemt_me_reconnect_success_total 21964
telemt_me_reader_eof_total 23273
telemt_me_idle_close_by_peer_total 23270
telemt_me_route_drop_no_conn_total 384021
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 847802
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3365
telemt_desync_full_logged_total 1095
telemt_desync_suppressed_total 2270
telemt_desync_frames_bucket_total{bucket="1_2"} 1094
telemt_desync_frames_bucket_total{bucket="3_10"} 1188
telemt_desync_frames_bucket_total{bucket="gt_10"} 1083
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 22288
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 21941
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 86
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 850241
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 10285099938 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 250389290828 (233.19 GB)
telemt_user_msgs_from_client{user="hello"} 7933
telemt_user_msgs_to_client{user="hello"} 11226
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 109361.0 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1766178
telemt_connections_bad_total 11157
telemt_handshake_timeouts_total 135965
telemt_upstream_connect_attempt_total 27580
telemt_upstream_connect_success_total 27228
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 27580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12338
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 137
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 2041
telemt_me_reconnect_attempts_total 59740
telemt_me_reconnect_success_total 20611
telemt_me_reader_eof_total 22693
telemt_me_idle_close_by_peer_total 22693
telemt_me_route_drop_no_conn_total 641977
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1553309
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4182
telemt_desync_full_logged_total 1235
telemt_desync_suppressed_total 2947
telemt_desync_frames_bucket_total{bucket="1_2"} 974
telemt_desync_frames_bucket_total{bucket="3_10"} 1589
telemt_desync_frames_bucket_total{bucket="gt_10"} 1619
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 22116
telemt_me_refill_failed_total 1217
telemt_me_writer_restored_same_endpoint_total 20599
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 4370
telemt_me_writer_removed_unexpected_minus_restored_total 1505
telemt_user_connections_total{user="hello"} 1552938
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 19895866257 (18.53 GB)
telemt_user_octets_to_client{user="hello"} 475989803437 (443.30 GB)
telemt_user_msgs_from_client{user="hello"} 2827
telemt_user_msgs_to_client{user="hello"} 7517
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 109361.3 (30h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1263446
telemt_connections_bad_total 78251
telemt_handshake_timeouts_total 111546
telemt_upstream_connect_attempt_total 29425
telemt_upstream_connect_success_total 29425
telemt_upstream_connect_attempts_per_request{bucket="1"} 29425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13403
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 1536
telemt_me_reconnect_attempts_total 28568
telemt_me_reconnect_success_total 23948
telemt_me_reader_eof_total 25433
telemt_me_idle_close_by_peer_total 25432
telemt_me_seq_mismatch_total 23
telemt_me_route_drop_no_conn_total 424941
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1037797
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2205
telemt_desync_full_logged_total 829
telemt_desync_suppressed_total 1376
telemt_desync_frames_bucket_total{bucket="1_2"} 780
telemt_desync_frames_bucket_total{bucket="3_10"} 741
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 24347
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 23915
telemt_me_writer_restored_fallback_total 33
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 399
telemt_user_connections_total{user="hello"} 1036922
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 12256844540 (11.42 GB)
telemt_user_octets_to_client{user="hello"} 314557287084 (292.95 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 14037.4 (3h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201650
telemt_connections_bad_total 5148
telemt_handshake_timeouts_total 2297
telemt_upstream_connect_attempt_total 4039
telemt_upstream_connect_success_total 4038
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 3304
telemt_me_reconnect_success_total 3274
telemt_me_reader_eof_total 3391
telemt_me_idle_close_by_peer_total 3391
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 68198
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177873
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 456
telemt_desync_full_logged_total 156
telemt_desync_suppressed_total 300
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 175
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 3311
telemt_me_writer_restored_same_endpoint_total 3249
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 256
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 177835
telemt_user_connections_current{user="hello"} 439
telemt_user_octets_from_client{user="hello"} 9597477460 (8.94 GB)
telemt_user_octets_to_client{user="hello"} 62921390916 (58.60 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 43
```