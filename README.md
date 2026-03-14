# Server Metrics 2026-03-14 04:27:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 167304.9 (46h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4762158
telemt_connections_bad_total 39896
telemt_handshake_timeouts_total 109806
telemt_upstream_connect_attempt_total 35294
telemt_upstream_connect_success_total 35062
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7297
telemt_me_reconnect_attempts_total 34558
telemt_me_reconnect_success_total 24415
telemt_me_reader_eof_total 26204
telemt_me_idle_close_by_peer_total 26203
telemt_me_route_drop_no_conn_total 1805505
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4368011
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16889
telemt_desync_full_logged_total 4556
telemt_desync_suppressed_total 12333
telemt_desync_frames_bucket_total{bucket="1_2"} 4215
telemt_desync_frames_bucket_total{bucket="3_10"} 6450
telemt_desync_frames_bucket_total{bucket="gt_10"} 6224
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 25078
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24402
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 663
telemt_user_connections_total{user="hello"} 4369587
telemt_user_connections_current{user="hello"} 867
telemt_user_octets_from_client{user="hello"} 63959661124 (59.57 GB)
telemt_user_octets_to_client{user="hello"} 1378460966905 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 278
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66968.7 (18h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 734792
telemt_connections_bad_total 52499
telemt_handshake_timeouts_total 13439
telemt_upstream_connect_attempt_total 18492
telemt_upstream_connect_success_total 18232
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18492
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10104
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7877
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 2099
telemt_me_reconnect_attempts_total 16309
telemt_me_reconnect_success_total 12856
telemt_me_reader_eof_total 13655
telemt_me_idle_close_by_peer_total 13654
telemt_me_route_drop_no_conn_total 244759
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 586882
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 507
telemt_desync_suppressed_total 1244
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 777
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 13141
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12848
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 285
telemt_user_connections_total{user="hello"} 588833
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 6301088977 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 196042356880 (182.58 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 196925.6 (54h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3430480
telemt_connections_bad_total 37015
telemt_handshake_timeouts_total 226175
telemt_upstream_connect_attempt_total 44525
telemt_upstream_connect_success_total 44504
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20836
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10604
telemt_me_reconnect_attempts_total 39374
telemt_me_reconnect_success_total 34405
telemt_me_reader_eof_total 36549
telemt_me_idle_close_by_peer_total 36548
telemt_me_route_drop_no_conn_total 1173091
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2857770
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9438
telemt_desync_full_logged_total 3156
telemt_desync_suppressed_total 6282
telemt_desync_frames_bucket_total{bucket="1_2"} 1640
telemt_desync_frames_bucket_total{bucket="3_10"} 3404
telemt_desync_frames_bucket_total{bucket="gt_10"} 4394
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 34884
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34364
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 2856985
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 45660896816 (42.53 GB)
telemt_user_octets_to_client{user="hello"} 1023836761273 (953.52 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 196928.0 (54h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2300026
telemt_connections_bad_total 23055
telemt_handshake_timeouts_total 257744
telemt_upstream_connect_attempt_total 61589
telemt_upstream_connect_success_total 59116
telemt_upstream_connect_fail_total 2336
telemt_upstream_connect_attempts_per_request{bucket="1"} 61315
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35324
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23626
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2335
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20457
telemt_me_reconnect_attempts_total 51344
telemt_me_reconnect_success_total 42306
telemt_me_reader_eof_total 45373
telemt_me_idle_close_by_peer_total 45366
telemt_me_route_drop_no_conn_total 781289
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1825937
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3876
telemt_desync_full_logged_total 1246
telemt_desync_suppressed_total 2630
telemt_desync_frames_bucket_total{bucket="1_2"} 1044
telemt_desync_frames_bucket_total{bucket="3_10"} 1610
telemt_desync_frames_bucket_total{bucket="gt_10"} 1222
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 42953
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42282
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 1831888
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 27762936759 (25.86 GB)
telemt_user_octets_to_client{user="hello"} 673774339918 (627.50 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66361.6 (18h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729059
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 8737
telemt_upstream_connect_attempt_total 17145
telemt_upstream_connect_success_total 16688
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 17145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8770
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 1533
telemt_me_reconnect_attempts_total 52139
telemt_me_reconnect_success_total 13380
telemt_me_reader_eof_total 14927
telemt_me_idle_close_by_peer_total 14926
telemt_me_route_drop_no_conn_total 278368
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 680305
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 539
telemt_desync_suppressed_total 1180
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 668
telemt_desync_frames_bucket_total{bucket="gt_10"} 538
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 14705
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13375
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 680177
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 12343168584 (11.50 GB)
telemt_user_octets_to_client{user="hello"} 219662209864 (204.58 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 36
```