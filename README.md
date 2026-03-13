# Server Metrics 2026-03-13 23:25:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 149208.4 (41h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4568135
telemt_connections_bad_total 38388
telemt_handshake_timeouts_total 107679
telemt_upstream_connect_attempt_total 31314
telemt_upstream_connect_success_total 31100
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 31314
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 6649
telemt_me_reconnect_attempts_total 31463
telemt_me_reconnect_success_total 21334
telemt_me_reader_eof_total 22871
telemt_me_idle_close_by_peer_total 22870
telemt_me_route_drop_no_conn_total 1726859
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4185953
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16594
telemt_desync_full_logged_total 4468
telemt_desync_suppressed_total 12126
telemt_desync_frames_bucket_total{bucket="1_2"} 4131
telemt_desync_frames_bucket_total{bucket="3_10"} 6348
telemt_desync_frames_bucket_total{bucket="gt_10"} 6115
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 21959
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 21321
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 4187878
telemt_user_connections_current{user="hello"} 674
telemt_user_octets_from_client{user="hello"} 61431798620 (57.21 GB)
telemt_user_octets_to_client{user="hello"} 1324811470825 (1.20 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 217
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 48872.0 (13h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 609108
telemt_connections_bad_total 45039
telemt_handshake_timeouts_total 12573
telemt_upstream_connect_attempt_total 13851
telemt_upstream_connect_success_total 13613
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 13851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_keepalive_timeout_total 1923
telemt_me_reconnect_attempts_total 12554
telemt_me_reconnect_success_total 9117
telemt_me_reader_eof_total 9670
telemt_me_idle_close_by_peer_total 9669
telemt_me_route_drop_no_conn_total 220906
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 524979
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1643
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 1199
telemt_desync_frames_bucket_total{bucket="1_2"} 348
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 9359
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 9109
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 526930
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 5792129313 (5.39 GB)
telemt_user_octets_to_client{user="hello"} 172102283336 (160.28 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 178828.8 (49h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3313783
telemt_connections_bad_total 31947
telemt_handshake_timeouts_total 221872
telemt_upstream_connect_attempt_total 39731
telemt_upstream_connect_success_total 39710
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 39731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20742
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18739
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10338
telemt_me_reconnect_attempts_total 35445
telemt_me_reconnect_success_total 30490
telemt_me_reader_eof_total 32362
telemt_me_idle_close_by_peer_total 32361
telemt_me_route_drop_no_conn_total 1136927
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2753073
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9026
telemt_desync_full_logged_total 3035
telemt_desync_suppressed_total 5991
telemt_desync_frames_bucket_total{bucket="1_2"} 1519
telemt_desync_frames_bucket_total{bucket="3_10"} 3269
telemt_desync_frames_bucket_total{bucket="gt_10"} 4238
telemt_pool_swap_total 166
telemt_me_writer_removed_unexpected_total 30937
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 30449
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 447
telemt_user_connections_total{user="hello"} 2752325
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 44745057072 (41.67 GB)
telemt_user_octets_to_client{user="hello"} 973343667925 (906.50 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 178831.3 (49h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2179397
telemt_connections_bad_total 22853
telemt_handshake_timeouts_total 228921
telemt_upstream_connect_attempt_total 55712
telemt_upstream_connect_success_total 53260
telemt_upstream_connect_fail_total 2315
telemt_upstream_connect_attempts_per_request{bucket="1"} 55438
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2314
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20351
telemt_me_reconnect_attempts_total 46357
telemt_me_reconnect_success_total 37336
telemt_me_reader_eof_total 40045
telemt_me_idle_close_by_peer_total 40038
telemt_me_route_drop_no_conn_total 760071
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1767894
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3795
telemt_desync_full_logged_total 1216
telemt_desync_suppressed_total 2579
telemt_desync_frames_bucket_total{bucket="1_2"} 1002
telemt_desync_frames_bucket_total{bucket="3_10"} 1587
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 156
telemt_me_writer_removed_unexpected_total 37939
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 37312
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 603
telemt_user_connections_total{user="hello"} 1773782
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 27339850155 (25.46 GB)
telemt_user_octets_to_client{user="hello"} 661162442538 (615.76 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 48264.8 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 655241
telemt_connections_bad_total 7856
telemt_handshake_timeouts_total 7347
telemt_upstream_connect_attempt_total 11280
telemt_upstream_connect_success_total 10933
telemt_upstream_connect_fail_total 346
telemt_upstream_connect_attempts_per_request{bucket="1"} 11279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5664
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 346
telemt_me_keepalive_timeout_total 1441
telemt_me_reconnect_attempts_total 38230
telemt_me_reconnect_success_total 8508
telemt_me_reader_eof_total 9593
telemt_me_idle_close_by_peer_total 9592
telemt_me_route_drop_no_conn_total 248413
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 610363
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1609
telemt_desync_full_logged_total 506
telemt_desync_suppressed_total 1103
telemt_desync_frames_bucket_total{bucket="1_2"} 488
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 492
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 9519
telemt_me_refill_failed_total 925
telemt_me_writer_restored_same_endpoint_total 8503
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1011
telemt_user_connections_total{user="hello"} 610266
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 9734829780 (9.07 GB)
telemt_user_octets_to_client{user="hello"} 200004696220 (186.27 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 28
```