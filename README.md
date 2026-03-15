# Server Metrics 2026-03-15 13:54:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.18

telemt_uptime_seconds 56410.2 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1710316
telemt_connections_bad_total 97084
telemt_handshake_timeouts_total 17355
telemt_upstream_connect_attempt_total 11219
telemt_upstream_connect_success_total 11170
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 11219
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 13228
telemt_me_reconnect_success_total 8340
telemt_me_reader_eof_total 8940
telemt_me_idle_close_by_peer_total 8940
telemt_me_route_drop_no_conn_total 582586
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1442896
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5372
telemt_desync_full_logged_total 1493
telemt_desync_suppressed_total 3879
telemt_desync_frames_bucket_total{bucket="1_2"} 1384
telemt_desync_frames_bucket_total{bucket="3_10"} 2089
telemt_desync_frames_bucket_total{bucket="gt_10"} 1899
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8626
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 8329
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 296
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 1442532
telemt_user_connections_current{user="hello"} 2170
telemt_user_octets_from_client{user="hello"} 20703689152 (19.28 GB)
telemt_user_octets_to_client{user="hello"} 571027691740 (531.81 GB)
telemt_user_unique_ips_current{user="hello"} 630
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## server2

```
telemt 3.3.18

telemt_uptime_seconds 56411.0 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 691886
telemt_connections_bad_total 36988
telemt_handshake_timeouts_total 53238
telemt_upstream_connect_attempt_total 14485
telemt_upstream_connect_success_total 14415
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 14485
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7728
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6556
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 35
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 11336
telemt_me_reconnect_success_total 11250
telemt_me_reader_eof_total 11888
telemt_me_idle_close_by_peer_total 11888
telemt_me_route_drop_no_conn_total 171947
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 520149
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 16
telemt_me_endpoint_quarantine_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1973
telemt_desync_full_logged_total 681
telemt_desync_suppressed_total 1292
telemt_desync_frames_bucket_total{bucket="1_2"} 734
telemt_desync_frames_bucket_total{bucket="3_10"} 719
telemt_desync_frames_bucket_total{bucket="gt_10"} 520
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11387
telemt_me_writer_restored_same_endpoint_total 11238
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 520415
telemt_user_connections_current{user="hello"} 682
telemt_user_octets_from_client{user="hello"} 7355631911 (6.85 GB)
telemt_user_octets_to_client{user="hello"} 197113901368 (183.58 GB)
telemt_user_msgs_from_client{user="hello"} 620
telemt_user_msgs_to_client{user="hello"} 1332
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.18

telemt_uptime_seconds 56410.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1470283
telemt_connections_bad_total 43927
telemt_handshake_timeouts_total 152257
telemt_upstream_connect_attempt_total 12465
telemt_upstream_connect_success_total 12408
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 12465
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 10815
telemt_me_reconnect_success_total 9563
telemt_me_reader_eof_total 10139
telemt_me_idle_close_by_peer_total 10139
telemt_me_route_drop_no_conn_total 401353
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920314
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2347
telemt_desync_full_logged_total 862
telemt_desync_suppressed_total 1485
telemt_desync_frames_bucket_total{bucket="1_2"} 528
telemt_desync_frames_bucket_total{bucket="3_10"} 900
telemt_desync_frames_bucket_total{bucket="gt_10"} 919
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9726
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 9544
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 242
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 916777
telemt_user_connections_current{user="hello"} 1257
telemt_user_octets_from_client{user="hello"} 13215818680 (12.31 GB)
telemt_user_octets_to_client{user="hello"} 332804434020 (309.95 GB)
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## server4

```
telemt 3.3.18

telemt_uptime_seconds 56411.0 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 704939
telemt_connections_bad_total 70454
telemt_handshake_timeouts_total 37693
telemt_upstream_connect_attempt_total 102543
telemt_upstream_connect_success_total 102092
telemt_upstream_connect_fail_total 450
telemt_upstream_connect_attempts_per_request{bucket="1"} 102542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 450
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 48125
telemt_me_reconnect_success_total 11788
telemt_me_reader_eof_total 13255
telemt_me_idle_close_by_peer_total 13255
telemt_me_seq_mismatch_total 19
telemt_me_route_drop_no_conn_total 169534
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 443301
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1167
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 872
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 474
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 13034
telemt_me_refill_failed_total 1136
telemt_me_writer_restored_same_endpoint_total 11756
telemt_me_writer_restored_fallback_total 32
telemt_me_async_recovery_trigger_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 1246
telemt_user_connections_total{user="hello"} 530653
telemt_user_connections_current{user="hello"} 873
telemt_user_octets_from_client{user="hello"} 9787978223 (9.12 GB)
telemt_user_octets_to_client{user="hello"} 181737370275 (169.26 GB)
telemt_user_msgs_from_client{user="hello"} 1672308
telemt_user_msgs_to_client{user="hello"} 6220737
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## server5

```
telemt 3.3.18

telemt_uptime_seconds 56411.9 (15h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 730899
telemt_connections_bad_total 9140
telemt_handshake_timeouts_total 15314
telemt_upstream_connect_attempt_total 12414
telemt_upstream_connect_success_total 12346
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 12414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6643
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 13193
telemt_me_reconnect_success_total 9519
telemt_me_reader_eof_total 10194
telemt_me_idle_close_by_peer_total 10194
telemt_me_route_drop_no_conn_total 182131
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 595301
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2203
telemt_desync_full_logged_total 741
telemt_desync_suppressed_total 1462
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 863
telemt_desync_frames_bucket_total{bucket="gt_10"} 681
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9748
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 9511
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 595341
telemt_user_connections_current{user="hello"} 852
telemt_user_octets_from_client{user="hello"} 7458076040 (6.95 GB)
telemt_user_octets_to_client{user="hello"} 223887387868 (208.51 GB)
telemt_user_unique_ips_current{user="hello"} 238
telemt_user_unique_ips_recent_window{user="hello"} 106
```