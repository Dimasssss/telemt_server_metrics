# Server Metrics 2026-03-13 18:39:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 132065.6 (36h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4221871
telemt_connections_bad_total 37746
telemt_handshake_timeouts_total 102560
telemt_upstream_connect_attempt_total 27848
telemt_upstream_connect_success_total 27665
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 27848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12232
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 5787
telemt_me_reconnect_attempts_total 28849
telemt_me_reconnect_success_total 18741
telemt_me_reader_eof_total 20127
telemt_me_idle_close_by_peer_total 20126
telemt_me_route_drop_no_conn_total 1580162
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3858522
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15130
telemt_desync_full_logged_total 4020
telemt_desync_suppressed_total 11110
telemt_desync_frames_bucket_total{bucket="1_2"} 3764
telemt_desync_frames_bucket_total{bucket="3_10"} 5756
telemt_desync_frames_bucket_total{bucket="gt_10"} 5610
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 19324
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 18728
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 3860692
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 54319400240 (50.59 GB)
telemt_user_octets_to_client{user="hello"} 1208955583849 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 31729.4 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 467634
telemt_connections_bad_total 36492
telemt_handshake_timeouts_total 10781
telemt_upstream_connect_attempt_total 8994
telemt_upstream_connect_success_total 8811
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 8994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3615
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_timeout_total 1632
telemt_me_reconnect_attempts_total 9165
telemt_me_reconnect_success_total 5764
telemt_me_reader_eof_total 6095
telemt_me_idle_close_by_peer_total 6094
telemt_me_route_drop_no_conn_total 176110
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 406957
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1429
telemt_desync_full_logged_total 377
telemt_desync_suppressed_total 1052
telemt_desync_frames_bucket_total{bucket="1_2"} 285
telemt_desync_frames_bucket_total{bucket="3_10"} 653
telemt_desync_frames_bucket_total{bucket="gt_10"} 491
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 5947
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 5756
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 408293
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 4283074171 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 126674472844 (117.97 GB)
telemt_user_msgs_from_client{user="hello"} 4402
telemt_user_msgs_to_client{user="hello"} 9145
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 161686.1 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3084812
telemt_connections_bad_total 28928
telemt_handshake_timeouts_total 206724
telemt_upstream_connect_attempt_total 35952
telemt_upstream_connect_success_total 35942
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 35952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17223
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3519
telemt_me_reconnect_attempts_total 30126
telemt_me_reconnect_success_total 27571
telemt_me_reader_eof_total 29235
telemt_me_idle_close_by_peer_total 29234
telemt_me_route_drop_no_conn_total 1055053
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2551327
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8596
telemt_desync_full_logged_total 2849
telemt_desync_suppressed_total 5747
telemt_desync_frames_bucket_total{bucket="1_2"} 1404
telemt_desync_frames_bucket_total{bucket="3_10"} 3146
telemt_desync_frames_bucket_total{bucket="gt_10"} 4046
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 27893
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 27530
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 2550630
telemt_user_connections_current{user="hello"} 912
telemt_user_octets_from_client{user="hello"} 42052567120 (39.16 GB)
telemt_user_octets_to_client{user="hello"} 896521116497 (834.95 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 161686.6 (44h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1983625
telemt_connections_bad_total 20257
telemt_handshake_timeouts_total 182112
telemt_upstream_connect_attempt_total 49871
telemt_upstream_connect_success_total 47525
telemt_upstream_connect_fail_total 2209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49597
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28386
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19048
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2208
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11988
telemt_me_reconnect_attempts_total 42615
telemt_me_reconnect_success_total 33628
telemt_me_reader_eof_total 36107
telemt_me_idle_close_by_peer_total 36100
telemt_me_route_drop_no_conn_total 706454
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1637835
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3352
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 2268
telemt_desync_frames_bucket_total{bucket="1_2"} 911
telemt_desync_frames_bucket_total{bucket="3_10"} 1366
telemt_desync_frames_bucket_total{bucket="gt_10"} 1075
telemt_pool_swap_total 141
telemt_me_writer_removed_unexpected_total 34182
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 33604
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 1642530
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 25259624341 (23.52 GB)
telemt_user_octets_to_client{user="hello"} 621717240762 (579.02 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 187
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 31122.4 (8h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507578
telemt_connections_bad_total 4736
telemt_handshake_timeouts_total 5134
telemt_upstream_connect_attempt_total 6858
telemt_upstream_connect_success_total 6637
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 6858
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 23269
telemt_me_reconnect_success_total 5061
telemt_me_reader_eof_total 5727
telemt_me_idle_close_by_peer_total 5727
telemt_me_route_drop_no_conn_total 192894
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 475578
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1376
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 937
telemt_desync_frames_bucket_total{bucket="1_2"} 430
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 405
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 5671
telemt_me_refill_failed_total 567
telemt_me_writer_restored_same_endpoint_total 5057
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 475546
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 5483509896 (5.11 GB)
telemt_user_octets_to_client{user="hello"} 152575063784 (142.10 GB)
telemt_user_unique_ips_current{user="hello"} 194
telemt_user_unique_ips_recent_window{user="hello"} 81
```