# Server Metrics 2026-03-14 05:33:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 171292.9 (47h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4839213
telemt_connections_bad_total 40016
telemt_handshake_timeouts_total 110887
telemt_upstream_connect_attempt_total 36075
telemt_upstream_connect_success_total 35839
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 36075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_keepalive_timeout_total 7305
telemt_me_reconnect_attempts_total 35118
telemt_me_reconnect_success_total 24972
telemt_me_reader_eof_total 26806
telemt_me_idle_close_by_peer_total 26805
telemt_me_route_drop_no_conn_total 1832016
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4439981
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17101
telemt_desync_full_logged_total 4618
telemt_desync_suppressed_total 12483
telemt_desync_frames_bucket_total{bucket="1_2"} 4270
telemt_desync_frames_bucket_total{bucket="3_10"} 6532
telemt_desync_frames_bucket_total{bucket="gt_10"} 6299
telemt_pool_swap_total 150
telemt_me_writer_removed_unexpected_total 25646
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24959
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 674
telemt_user_connections_total{user="hello"} 4441530
telemt_user_connections_current{user="hello"} 952
telemt_user_octets_from_client{user="hello"} 64913160472 (60.46 GB)
telemt_user_octets_to_client{user="hello"} 1402321922097 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70956.8 (19h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 775047
telemt_connections_bad_total 53072
telemt_handshake_timeouts_total 14218
telemt_upstream_connect_attempt_total 19450
telemt_upstream_connect_success_total 19182
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 19450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10580
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8346
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 2114
telemt_me_reconnect_attempts_total 17087
telemt_me_reconnect_success_total 13628
telemt_me_reader_eof_total 14480
telemt_me_idle_close_by_peer_total 14479
telemt_me_route_drop_no_conn_total 253251
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 611200
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1828
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1284
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 629
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13921
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13620
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 613152
telemt_user_connections_current{user="hello"} 353
telemt_user_octets_from_client{user="hello"} 6522446025 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 207705397192 (193.44 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 200913.6 (55h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3478193
telemt_connections_bad_total 38104
telemt_handshake_timeouts_total 230057
telemt_upstream_connect_attempt_total 45451
telemt_upstream_connect_success_total 45430
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10631
telemt_me_reconnect_attempts_total 40084
telemt_me_reconnect_success_total 35113
telemt_me_reader_eof_total 37308
telemt_me_idle_close_by_peer_total 37307
telemt_me_route_drop_no_conn_total 1189065
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2897712
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9573
telemt_desync_full_logged_total 3218
telemt_desync_suppressed_total 6355
telemt_desync_frames_bucket_total{bucket="1_2"} 1661
telemt_desync_frames_bucket_total{bucket="3_10"} 3468
telemt_desync_frames_bucket_total{bucket="gt_10"} 4444
telemt_pool_swap_total 191
telemt_me_writer_removed_unexpected_total 35600
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35072
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 2896924
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 46349528328 (43.17 GB)
telemt_user_octets_to_client{user="hello"} 1037805894177 (966.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 200916.1 (55h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2329301
telemt_connections_bad_total 23131
telemt_handshake_timeouts_total 267208
telemt_upstream_connect_attempt_total 62817
telemt_upstream_connect_success_total 60335
telemt_upstream_connect_fail_total 2345
telemt_upstream_connect_attempts_per_request{bucket="1"} 62543
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2344
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20476
telemt_me_reconnect_attempts_total 52346
telemt_me_reconnect_success_total 43304
telemt_me_reader_eof_total 46440
telemt_me_idle_close_by_peer_total 46433
telemt_me_route_drop_no_conn_total 788316
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1844193
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3886
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2633
telemt_desync_frames_bucket_total{bucket="1_2"} 1045
telemt_desync_frames_bucket_total{bucket="3_10"} 1615
telemt_desync_frames_bucket_total{bucket="gt_10"} 1226
telemt_pool_swap_total 178
telemt_me_writer_removed_unexpected_total 43963
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43280
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 659
telemt_user_connections_total{user="hello"} 1850184
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 28051599735 (26.13 GB)
telemt_user_octets_to_client{user="hello"} 679861183734 (633.17 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70349.5 (19h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 753841
telemt_connections_bad_total 8025
telemt_handshake_timeouts_total 8967
telemt_upstream_connect_attempt_total 18286
telemt_upstream_connect_success_total 17804
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 18286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 1558
telemt_me_reconnect_attempts_total 54714
telemt_me_reconnect_success_total 14274
telemt_me_reader_eof_total 15893
telemt_me_idle_close_by_peer_total 15892
telemt_me_route_drop_no_conn_total 288739
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703880
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1752
telemt_desync_full_logged_total 558
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 519
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15663
telemt_me_refill_failed_total 1259
telemt_me_writer_restored_same_endpoint_total 14269
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1389
telemt_user_connections_total{user="hello"} 703745
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 12613742868 (11.75 GB)
telemt_user_octets_to_client{user="hello"} 232938336980 (216.94 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 66
```