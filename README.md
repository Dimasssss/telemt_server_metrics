# Server Metrics 2026-03-13 19:10:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 133899.6 (37h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4280093
telemt_connections_bad_total 37750
telemt_handshake_timeouts_total 104297
telemt_upstream_connect_attempt_total 28123
telemt_upstream_connect_success_total 27933
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 28123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12361
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_timeout_total 6520
telemt_me_reconnect_attempts_total 29036
telemt_me_reconnect_success_total 18920
telemt_me_reader_eof_total 20310
telemt_me_idle_close_by_peer_total 20309
telemt_me_route_drop_no_conn_total 1605799
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3913056
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15423
telemt_desync_full_logged_total 4105
telemt_desync_suppressed_total 11318
telemt_desync_frames_bucket_total{bucket="1_2"} 3843
telemt_desync_frames_bucket_total{bucket="3_10"} 5870
telemt_desync_frames_bucket_total{bucket="gt_10"} 5710
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 19507
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18907
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 587
telemt_user_connections_total{user="hello"} 3915227
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 56306383536 (52.44 GB)
telemt_user_octets_to_client{user="hello"} 1229191519693 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 33563.6 (9h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490804
telemt_connections_bad_total 38327
telemt_handshake_timeouts_total 10950
telemt_upstream_connect_attempt_total 9974
telemt_upstream_connect_success_total 9761
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 9974
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 1863
telemt_me_reconnect_attempts_total 9437
telemt_me_reconnect_success_total 6025
telemt_me_reader_eof_total 6372
telemt_me_idle_close_by_peer_total 6371
telemt_me_route_drop_no_conn_total 184545
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426873
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1500
telemt_desync_full_logged_total 401
telemt_desync_suppressed_total 1099
telemt_desync_frames_bucket_total{bucket="1_2"} 305
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 518
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6215
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 6017
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 428802
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 4538420645 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 135170758892 (125.89 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 163520.1 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3128828
telemt_connections_bad_total 29160
telemt_handshake_timeouts_total 209840
telemt_upstream_connect_attempt_total 36348
telemt_upstream_connect_success_total 36333
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 36348
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 139
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 10172
telemt_me_reconnect_attempts_total 30436
telemt_me_reconnect_success_total 27873
telemt_me_reader_eof_total 29541
telemt_me_idle_close_by_peer_total 29540
telemt_me_route_drop_no_conn_total 1068974
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2585631
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8685
telemt_desync_full_logged_total 2875
telemt_desync_suppressed_total 5810
telemt_desync_frames_bucket_total{bucket="1_2"} 1423
telemt_desync_frames_bucket_total{bucket="3_10"} 3179
telemt_desync_frames_bucket_total{bucket="gt_10"} 4083
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 28203
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27832
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 2584924
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 42428740988 (39.51 GB)
telemt_user_octets_to_client{user="hello"} 907604599761 (845.27 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 163520.6 (45h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2014935
telemt_connections_bad_total 21562
telemt_handshake_timeouts_total 184229
telemt_upstream_connect_attempt_total 51507
telemt_upstream_connect_success_total 49073
telemt_upstream_connect_fail_total 2297
telemt_upstream_connect_attempts_per_request{bucket="1"} 51233
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19268
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2296
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20183
telemt_me_reconnect_attempts_total 42912
telemt_me_reconnect_success_total 33907
telemt_me_reader_eof_total 36405
telemt_me_idle_close_by_peer_total 36398
telemt_me_route_drop_no_conn_total 716722
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1663520
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3483
telemt_desync_full_logged_total 1118
telemt_desync_suppressed_total 2365
telemt_desync_frames_bucket_total{bucket="1_2"} 935
telemt_desync_frames_bucket_total{bucket="3_10"} 1430
telemt_desync_frames_bucket_total{bucket="gt_10"} 1118
telemt_pool_swap_total 143
telemt_me_writer_removed_unexpected_total 34468
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33883
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 1669392
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 25575018227 (23.82 GB)
telemt_user_octets_to_client{user="hello"} 631941861322 (588.54 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 32956.1 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531811
telemt_connections_bad_total 5575
telemt_handshake_timeouts_total 5288
telemt_upstream_connect_attempt_total 7116
telemt_upstream_connect_success_total 6878
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 7116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3615
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 954
telemt_me_reconnect_attempts_total 26145
telemt_me_reconnect_success_total 5211
telemt_me_reader_eof_total 5955
telemt_me_idle_close_by_peer_total 5954
telemt_me_route_drop_no_conn_total 201871
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 497857
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1454
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 1003
telemt_desync_frames_bucket_total{bucket="1_2"} 438
telemt_desync_frames_bucket_total{bucket="3_10"} 583
telemt_desync_frames_bucket_total{bucket="gt_10"} 433
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5907
telemt_me_refill_failed_total 652
telemt_me_writer_restored_same_endpoint_total 5207
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 696
telemt_user_connections_total{user="hello"} 497838
telemt_user_connections_current{user="hello"} 719
telemt_user_octets_from_client{user="hello"} 5770529028 (5.37 GB)
telemt_user_octets_to_client{user="hello"} 159434056352 (148.48 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 83
```