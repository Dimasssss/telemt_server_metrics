# Server Metrics 2026-03-13 13:38:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 113998.3 (31h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3450695
telemt_connections_bad_total 37374
telemt_handshake_timeouts_total 59105
telemt_upstream_connect_attempt_total 22362
telemt_upstream_connect_success_total 22238
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 2122
telemt_me_reconnect_attempts_total 26653
telemt_me_reconnect_success_total 16569
telemt_me_reader_eof_total 17809
telemt_me_idle_close_by_peer_total 17808
telemt_me_route_drop_no_conn_total 1280408
telemt_me_route_drop_channel_closed_total 16
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3166301
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13170
telemt_desync_full_logged_total 3441
telemt_desync_suppressed_total 9729
telemt_desync_frames_bucket_total{bucket="1_2"} 3342
telemt_desync_frames_bucket_total{bucket="3_10"} 4986
telemt_desync_frames_bucket_total{bucket="gt_10"} 4842
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 17114
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 16556
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 545
telemt_user_connections_total{user="hello"} 3166178
telemt_user_connections_current{user="hello"} 1703
telemt_user_octets_from_client{user="hello"} 43598242264 (40.60 GB)
telemt_user_octets_to_client{user="hello"} 1010786508912 (941.37 GB)
telemt_user_unique_ips_current{user="hello"} 455
telemt_user_unique_ips_recent_window{user="hello"} 224
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 13662.2 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190547
telemt_connections_bad_total 10751
telemt_handshake_timeouts_total 4938
telemt_upstream_connect_attempt_total 3250
telemt_upstream_connect_success_total 3173
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1630
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1510
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 3656
telemt_me_reconnect_success_total 2425
telemt_me_reader_eof_total 2555
telemt_me_idle_close_by_peer_total 2555
telemt_me_route_drop_no_conn_total 69308
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170010
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 496
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 341
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2486
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 2418
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 170034
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 1691053224 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 48151326488 (44.84 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 143619.0 (39h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2594955
telemt_connections_bad_total 26837
telemt_handshake_timeouts_total 173189
telemt_upstream_connect_attempt_total 32525
telemt_upstream_connect_success_total 32515
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 32525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 3205
telemt_me_reconnect_attempts_total 27571
telemt_me_reconnect_success_total 25025
telemt_me_reader_eof_total 26534
telemt_me_idle_close_by_peer_total 26533
telemt_me_route_drop_no_conn_total 871354
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2115043
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7351
telemt_desync_full_logged_total 2398
telemt_desync_suppressed_total 4953
telemt_desync_frames_bucket_total{bucket="1_2"} 1160
telemt_desync_frames_bucket_total{bucket="3_10"} 2678
telemt_desync_frames_bucket_total{bucket="gt_10"} 3513
telemt_pool_swap_total 134
telemt_me_writer_removed_unexpected_total 25317
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 24984
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 2114468
telemt_user_connections_current{user="hello"} 1005
telemt_user_octets_from_client{user="hello"} 35339260504 (32.91 GB)
telemt_user_octets_to_client{user="hello"} 755413452737 (703.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 143619.3 (39h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1654338
telemt_connections_bad_total 18034
telemt_handshake_timeouts_total 117251
telemt_upstream_connect_attempt_total 45912
telemt_upstream_connect_success_total 43592
telemt_upstream_connect_fail_total 2183
telemt_upstream_connect_attempts_per_request{bucket="1"} 45638
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17218
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2182
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 11834
telemt_me_reconnect_attempts_total 39555
telemt_me_reconnect_success_total 30589
telemt_me_reader_eof_total 32889
telemt_me_idle_close_by_peer_total 32882
telemt_me_route_drop_no_conn_total 590016
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1383131
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2762
telemt_desync_full_logged_total 900
telemt_desync_suppressed_total 1862
telemt_desync_frames_bucket_total{bucket="1_2"} 742
telemt_desync_frames_bucket_total{bucket="3_10"} 1141
telemt_desync_frames_bucket_total{bucket="gt_10"} 879
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 31095
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 30565
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 1387855
telemt_user_connections_current{user="hello"} 720
telemt_user_octets_from_client{user="hello"} 21387334853 (19.92 GB)
telemt_user_octets_to_client{user="hello"} 539410342946 (502.37 GB)
telemt_user_msgs_from_client{user="hello"} 44500
telemt_user_msgs_to_client{user="hello"} 116355
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 13054.9 (3h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205602
telemt_connections_bad_total 3848
telemt_handshake_timeouts_total 1847
telemt_upstream_connect_attempt_total 2655
telemt_upstream_connect_success_total 2569
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 2655
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1207
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1359
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 9948
telemt_me_reconnect_success_total 1872
telemt_me_reader_eof_total 2137
telemt_me_idle_close_by_peer_total 2137
telemt_me_route_drop_no_conn_total 80036
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 192335
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 674
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 259
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 2125
telemt_me_refill_failed_total 251
telemt_me_writer_restored_same_endpoint_total 1868
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 192318
telemt_user_connections_current{user="hello"} 761
telemt_user_octets_from_client{user="hello"} 2026249752 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 58295984852 (54.29 GB)
telemt_user_unique_ips_current{user="hello"} 206
telemt_user_unique_ips_recent_window{user="hello"} 115
```