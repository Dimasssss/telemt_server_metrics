# Server Metrics 2026-03-14 04:11:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 166384.9 (46h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4747270
telemt_connections_bad_total 39895
telemt_handshake_timeouts_total 109587
telemt_upstream_connect_attempt_total 35142
telemt_upstream_connect_success_total 34910
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7295
telemt_me_reconnect_attempts_total 34449
telemt_me_reconnect_success_total 24306
telemt_me_reader_eof_total 26085
telemt_me_idle_close_by_peer_total 26084
telemt_me_route_drop_no_conn_total 1801053
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4354604
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16856
telemt_desync_full_logged_total 4547
telemt_desync_suppressed_total 12309
telemt_desync_frames_bucket_total{bucket="1_2"} 4207
telemt_desync_frames_bucket_total{bucket="3_10"} 6432
telemt_desync_frames_bucket_total{bucket="gt_10"} 6217
telemt_pool_swap_total 144
telemt_me_writer_removed_unexpected_total 24967
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24293
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 4356178
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 63756001836 (59.38 GB)
telemt_user_octets_to_client{user="hello"} 1374528119197 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66048.5 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 726231
telemt_connections_bad_total 52498
telemt_handshake_timeouts_total 13378
telemt_upstream_connect_attempt_total 18284
telemt_upstream_connect_success_total 18025
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 18284
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 2097
telemt_me_reconnect_attempts_total 16145
telemt_me_reconnect_success_total 12694
telemt_me_reader_eof_total 13481
telemt_me_idle_close_by_peer_total 13480
telemt_me_route_drop_no_conn_total 242735
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 581635
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1719
telemt_desync_full_logged_total 493
telemt_desync_suppressed_total 1226
telemt_desync_frames_bucket_total{bucket="1_2"} 363
telemt_desync_frames_bucket_total{bucket="3_10"} 762
telemt_desync_frames_bucket_total{bucket="gt_10"} 594
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 12977
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12686
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 583590
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 6232104473 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 193853646732 (180.54 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 196005.3 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3421036
telemt_connections_bad_total 36968
telemt_handshake_timeouts_total 224885
telemt_upstream_connect_attempt_total 44315
telemt_upstream_connect_success_total 44294
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10598
telemt_me_reconnect_attempts_total 39207
telemt_me_reconnect_success_total 34239
telemt_me_reader_eof_total 36373
telemt_me_idle_close_by_peer_total 36372
telemt_me_route_drop_no_conn_total 1170239
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2849825
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9419
telemt_desync_full_logged_total 3149
telemt_desync_suppressed_total 6270
telemt_desync_frames_bucket_total{bucket="1_2"} 1628
telemt_desync_frames_bucket_total{bucket="3_10"} 3400
telemt_desync_frames_bucket_total{bucket="gt_10"} 4391
telemt_pool_swap_total 185
telemt_me_writer_removed_unexpected_total 34715
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34198
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 476
telemt_user_connections_total{user="hello"} 2849043
telemt_user_connections_current{user="hello"} 482
telemt_user_octets_from_client{user="hello"} 45619780712 (42.49 GB)
telemt_user_octets_to_client{user="hello"} 1021246339401 (951.11 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 196007.7 (54h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2293749
telemt_connections_bad_total 23024
telemt_handshake_timeouts_total 255893
telemt_upstream_connect_attempt_total 61375
telemt_upstream_connect_success_total 58903
telemt_upstream_connect_fail_total 2335
telemt_upstream_connect_attempts_per_request{bucket="1"} 61101
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23529
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2334
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20453
telemt_me_reconnect_attempts_total 51174
telemt_me_reconnect_success_total 42137
telemt_me_reader_eof_total 45188
telemt_me_idle_close_by_peer_total 45181
telemt_me_route_drop_no_conn_total 779617
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1821937
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3855
telemt_desync_full_logged_total 1241
telemt_desync_suppressed_total 2614
telemt_desync_frames_bucket_total{bucket="1_2"} 1037
telemt_desync_frames_bucket_total{bucket="3_10"} 1598
telemt_desync_frames_bucket_total{bucket="gt_10"} 1220
telemt_pool_swap_total 173
telemt_me_writer_removed_unexpected_total 42779
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42113
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 642
telemt_user_connections_total{user="hello"} 1827883
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 27729842015 (25.83 GB)
telemt_user_octets_to_client{user="hello"} 672967057086 (626.75 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65441.2 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 723843
telemt_connections_bad_total 7965
telemt_handshake_timeouts_total 8726
telemt_upstream_connect_attempt_total 16958
telemt_upstream_connect_success_total 16506
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_timeout_total 1532
telemt_me_reconnect_attempts_total 52000
telemt_me_reconnect_success_total 13242
telemt_me_reader_eof_total 14780
telemt_me_idle_close_by_peer_total 14779
telemt_me_route_drop_no_conn_total 276271
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 675264
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1712
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1175
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 535
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 14566
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13237
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1324
telemt_user_connections_total{user="hello"} 675137
telemt_user_connections_current{user="hello"} 364
telemt_user_octets_from_client{user="hello"} 12268607148 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 218480857192 (203.48 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 40
```