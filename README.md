# Server Metrics 2026-03-14 00:52:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 154422.5 (42h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4613364
telemt_connections_bad_total 38549
telemt_handshake_timeouts_total 107906
telemt_upstream_connect_attempt_total 32588
telemt_upstream_connect_success_total 32370
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 32588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14519
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 6669
telemt_me_reconnect_attempts_total 32470
telemt_me_reconnect_success_total 22338
telemt_me_reader_eof_total 23946
telemt_me_idle_close_by_peer_total 23945
telemt_me_route_drop_no_conn_total 1747603
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4229455
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16651
telemt_desync_full_logged_total 4491
telemt_desync_suppressed_total 12160
telemt_desync_frames_bucket_total{bucket="1_2"} 4148
telemt_desync_frames_bucket_total{bucket="3_10"} 6364
telemt_desync_frames_bucket_total{bucket="gt_10"} 6139
telemt_pool_swap_total 131
telemt_me_writer_removed_unexpected_total 22974
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 22325
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 4231321
telemt_user_connections_current{user="hello"} 523
telemt_user_octets_from_client{user="hello"} 62403614608 (58.12 GB)
telemt_user_octets_to_client{user="hello"} 1337414207249 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 199
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 54086.1 (15h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658728
telemt_connections_bad_total 49203
telemt_handshake_timeouts_total 12887
telemt_upstream_connect_attempt_total 15154
telemt_upstream_connect_success_total 14908
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 15154
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6258
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 24
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_timeout_total 1945
telemt_me_reconnect_attempts_total 13600
telemt_me_reconnect_success_total 10158
telemt_me_reader_eof_total 10771
telemt_me_idle_close_by_peer_total 10770
telemt_me_route_drop_no_conn_total 227553
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 539500
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1649
telemt_desync_full_logged_total 447
telemt_desync_suppressed_total 1202
telemt_desync_frames_bucket_total{bucket="1_2"} 350
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10409
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 10150
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 251
telemt_user_connections_total{user="hello"} 541451
telemt_user_connections_current{user="hello"} 219
telemt_user_octets_from_client{user="hello"} 5865335261 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 175615011420 (163.55 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 184042.9 (51h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3342716
telemt_connections_bad_total 34172
telemt_handshake_timeouts_total 222508
telemt_upstream_connect_attempt_total 41220
telemt_upstream_connect_success_total 41199
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 41220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19369
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10358
telemt_me_reconnect_attempts_total 36674
telemt_me_reconnect_success_total 31717
telemt_me_reader_eof_total 33672
telemt_me_idle_close_by_peer_total 33671
telemt_me_route_drop_no_conn_total 1147155
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2778492
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9141
telemt_desync_full_logged_total 3070
telemt_desync_suppressed_total 6071
telemt_desync_frames_bucket_total{bucket="1_2"} 1538
telemt_desync_frames_bucket_total{bucket="3_10"} 3313
telemt_desync_frames_bucket_total{bucket="gt_10"} 4290
telemt_pool_swap_total 172
telemt_me_writer_removed_unexpected_total 32172
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 31676
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 2777730
telemt_user_connections_current{user="hello"} 351
telemt_user_octets_from_client{user="hello"} 44913314868 (41.83 GB)
telemt_user_octets_to_client{user="hello"} 987151821877 (919.36 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 184045.4 (51h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2219526
telemt_connections_bad_total 22918
telemt_handshake_timeouts_total 238947
telemt_upstream_connect_attempt_total 57297
telemt_upstream_connect_success_total 54839
telemt_upstream_connect_fail_total 2321
telemt_upstream_connect_attempts_per_request{bucket="1"} 57023
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2320
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20387
telemt_me_reconnect_attempts_total 47678
telemt_me_reconnect_success_total 38652
telemt_me_reader_eof_total 41468
telemt_me_idle_close_by_peer_total 41461
telemt_me_route_drop_no_conn_total 765817
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1783594
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3800
telemt_desync_full_logged_total 1220
telemt_desync_suppressed_total 2580
telemt_desync_frames_bucket_total{bucket="1_2"} 1006
telemt_desync_frames_bucket_total{bucket="3_10"} 1588
telemt_desync_frames_bucket_total{bucket="gt_10"} 1206
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 39266
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 38628
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 1789509
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 27396312039 (25.51 GB)
telemt_user_octets_to_client{user="hello"} 663493709730 (617.93 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 53478.6 (14h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677710
telemt_connections_bad_total 7878
telemt_handshake_timeouts_total 8609
telemt_upstream_connect_attempt_total 13115
telemt_upstream_connect_success_total 12740
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 13115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6549
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_keepalive_timeout_total 1468
telemt_me_reconnect_attempts_total 42206
telemt_me_reconnect_success_total 10049
telemt_me_reader_eof_total 11279
telemt_me_idle_close_by_peer_total 11278
telemt_me_route_drop_no_conn_total 256023
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 630318
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1638
telemt_desync_full_logged_total 513
telemt_desync_suppressed_total 1125
telemt_desync_frames_bucket_total{bucket="1_2"} 492
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 505
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 11142
telemt_me_refill_failed_total 1001
telemt_me_writer_restored_same_endpoint_total 10044
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1093
telemt_user_connections_total{user="hello"} 630217
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 10545589860 (9.82 GB)
telemt_user_octets_to_client{user="hello"} 207210227764 (192.98 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 26
```