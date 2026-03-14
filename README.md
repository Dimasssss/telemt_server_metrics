# Server Metrics 2026-03-14 05:28:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 170986.4 (47h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4832704
telemt_connections_bad_total 40016
telemt_handshake_timeouts_total 110596
telemt_upstream_connect_attempt_total 35962
telemt_upstream_connect_success_total 35727
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 35962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19441
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_keepalive_timeout_total 7304
telemt_me_reconnect_attempts_total 35049
telemt_me_reconnect_success_total 24903
telemt_me_reader_eof_total 26728
telemt_me_idle_close_by_peer_total 26727
telemt_me_route_drop_no_conn_total 1829656
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4434359
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 17086
telemt_desync_full_logged_total 4612
telemt_desync_suppressed_total 12474
telemt_desync_frames_bucket_total{bucket="1_2"} 4264
telemt_desync_frames_bucket_total{bucket="3_10"} 6527
telemt_desync_frames_bucket_total{bucket="gt_10"} 6295
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 25575
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24890
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 672
telemt_user_connections_total{user="hello"} 4435909
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 64847653984 (60.39 GB)
telemt_user_octets_to_client{user="hello"} 1400497851121 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 70650.0 (19h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 771667
telemt_connections_bad_total 53072
telemt_handshake_timeouts_total 14190
telemt_upstream_connect_attempt_total 19401
telemt_upstream_connect_success_total 19133
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 19401
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8320
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 225
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 2114
telemt_me_reconnect_attempts_total 17038
telemt_me_reconnect_success_total 13579
telemt_me_reader_eof_total 14430
telemt_me_idle_close_by_peer_total 14429
telemt_me_route_drop_no_conn_total 252612
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 609074
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1826
telemt_desync_full_logged_total 542
telemt_desync_suppressed_total 1284
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 814
telemt_desync_frames_bucket_total{bucket="gt_10"} 629
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 13871
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 13571
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 292
telemt_user_connections_total{user="hello"} 611027
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 6506214761 (6.06 GB)
telemt_user_octets_to_client{user="hello"} 207152146388 (192.93 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 200606.8 (55h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3474054
telemt_connections_bad_total 38102
telemt_handshake_timeouts_total 229783
telemt_upstream_connect_attempt_total 45344
telemt_upstream_connect_success_total 45323
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 45344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21216
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10631
telemt_me_reconnect_attempts_total 40020
telemt_me_reconnect_success_total 35049
telemt_me_reader_eof_total 37231
telemt_me_idle_close_by_peer_total 37230
telemt_me_route_drop_no_conn_total 1187427
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2893887
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9563
telemt_desync_full_logged_total 3213
telemt_desync_suppressed_total 6350
telemt_desync_frames_bucket_total{bucket="1_2"} 1660
telemt_desync_frames_bucket_total{bucket="3_10"} 3466
telemt_desync_frames_bucket_total{bucket="gt_10"} 4437
telemt_pool_swap_total 190
telemt_me_writer_removed_unexpected_total 35536
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 35008
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 2893099
telemt_user_connections_current{user="hello"} 533
telemt_user_octets_from_client{user="hello"} 46312850360 (43.13 GB)
telemt_user_octets_to_client{user="hello"} 1036707876449 (965.51 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 200609.3 (55h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2326901
telemt_connections_bad_total 23131
telemt_handshake_timeouts_total 266460
telemt_upstream_connect_attempt_total 62684
telemt_upstream_connect_success_total 60204
telemt_upstream_connect_fail_total 2342
telemt_upstream_connect_attempts_per_request{bucket="1"} 62409
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35974
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2341
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20474
telemt_me_reconnect_attempts_total 52259
telemt_me_reconnect_success_total 43215
telemt_me_reader_eof_total 46334
telemt_me_idle_close_by_peer_total 46327
telemt_me_route_drop_no_conn_total 787847
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1842693
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
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 43876
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 43191
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 1848679
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 28036753019 (26.11 GB)
telemt_user_octets_to_client{user="hello"} 678494571646 (631.90 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 70042.6 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 751673
telemt_connections_bad_total 8025
telemt_handshake_timeouts_total 8955
telemt_upstream_connect_attempt_total 18188
telemt_upstream_connect_success_total 17713
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 18188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 1548
telemt_me_reconnect_attempts_total 54090
telemt_me_reconnect_success_total 14226
telemt_me_reader_eof_total 15825
telemt_me_idle_close_by_peer_total 15824
telemt_me_route_drop_no_conn_total 287659
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 701791
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1751
telemt_desync_full_logged_total 557
telemt_desync_suppressed_total 1194
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 686
telemt_desync_frames_bucket_total{bucket="gt_10"} 547
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 15595
telemt_me_refill_failed_total 1241
telemt_me_writer_restored_same_endpoint_total 14221
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1369
telemt_user_connections_total{user="hello"} 701656
telemt_user_connections_current{user="hello"} 385
telemt_user_octets_from_client{user="hello"} 12589445920 (11.72 GB)
telemt_user_octets_to_client{user="hello"} 232526587344 (216.56 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 53
```