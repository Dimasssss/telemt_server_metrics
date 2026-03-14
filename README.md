# Server Metrics 2026-03-14 04:16:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 166691.5 (46h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4751761
telemt_connections_bad_total 39896
telemt_handshake_timeouts_total 109651
telemt_upstream_connect_attempt_total 35237
telemt_upstream_connect_success_total 35005
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35237
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7295
telemt_me_reconnect_attempts_total 34501
telemt_me_reconnect_success_total 24358
telemt_me_reader_eof_total 26145
telemt_me_idle_close_by_peer_total 26144
telemt_me_route_drop_no_conn_total 1802442
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4358868
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16860
telemt_desync_full_logged_total 4549
telemt_desync_suppressed_total 12311
telemt_desync_frames_bucket_total{bucket="1_2"} 4207
telemt_desync_frames_bucket_total{bucket="3_10"} 6435
telemt_desync_frames_bucket_total{bucket="gt_10"} 6218
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 25019
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24345
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 661
telemt_user_connections_total{user="hello"} 4360442
telemt_user_connections_current{user="hello"} 874
telemt_user_octets_from_client{user="hello"} 63863925764 (59.48 GB)
telemt_user_octets_to_client{user="hello"} 1376334551021 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 275
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66355.2 (18h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 729208
telemt_connections_bad_total 52498
telemt_handshake_timeouts_total 13391
telemt_upstream_connect_attempt_total 18334
telemt_upstream_connect_success_total 18075
telemt_upstream_connect_fail_total 259
telemt_upstream_connect_attempts_per_request{bucket="1"} 18334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 259
telemt_me_keepalive_timeout_total 2097
telemt_me_reconnect_attempts_total 16195
telemt_me_reconnect_success_total 12743
telemt_me_reader_eof_total 13531
telemt_me_idle_close_by_peer_total 13530
telemt_me_route_drop_no_conn_total 243346
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 583438
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1732
telemt_desync_full_logged_total 499
telemt_desync_suppressed_total 1233
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 766
telemt_desync_frames_bucket_total{bucket="gt_10"} 600
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13027
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12735
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 585393
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 6251670981 (5.82 GB)
telemt_user_octets_to_client{user="hello"} 194100528876 (180.77 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 196312.0 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3424113
telemt_connections_bad_total 36978
telemt_handshake_timeouts_total 225319
telemt_upstream_connect_attempt_total 44392
telemt_upstream_connect_success_total 44371
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44392
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10601
telemt_me_reconnect_attempts_total 39241
telemt_me_reconnect_success_total 34273
telemt_me_reader_eof_total 36409
telemt_me_idle_close_by_peer_total 36408
telemt_me_route_drop_no_conn_total 1171103
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2852406
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9421
telemt_desync_full_logged_total 3150
telemt_desync_suppressed_total 6271
telemt_desync_frames_bucket_total{bucket="1_2"} 1630
telemt_desync_frames_bucket_total{bucket="3_10"} 3400
telemt_desync_frames_bucket_total{bucket="gt_10"} 4391
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 34751
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34232
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 2851622
telemt_user_connections_current{user="hello"} 425
telemt_user_octets_from_client{user="hello"} 45630907588 (42.50 GB)
telemt_user_octets_to_client{user="hello"} 1022036786529 (951.85 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 196314.6 (54h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2295730
telemt_connections_bad_total 23041
telemt_handshake_timeouts_total 256479
telemt_upstream_connect_attempt_total 61463
telemt_upstream_connect_success_total 58990
telemt_upstream_connect_fail_total 2336
telemt_upstream_connect_attempts_per_request{bucket="1"} 61189
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23564
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2335
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20453
telemt_me_reconnect_attempts_total 51218
telemt_me_reconnect_success_total 42181
telemt_me_reader_eof_total 45234
telemt_me_idle_close_by_peer_total 45227
telemt_me_route_drop_no_conn_total 780102
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1823149
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
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 42823
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42157
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 642
telemt_user_connections_total{user="hello"} 1829097
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 27736313019 (25.83 GB)
telemt_user_octets_to_client{user="hello"} 673158340974 (626.93 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 65747.7 (18h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 725459
telemt_connections_bad_total 7966
telemt_handshake_timeouts_total 8730
telemt_upstream_connect_attempt_total 17007
telemt_upstream_connect_success_total 16552
telemt_upstream_connect_fail_total 454
telemt_upstream_connect_attempts_per_request{bucket="1"} 17006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 454
telemt_me_keepalive_timeout_total 1532
telemt_me_reconnect_attempts_total 52038
telemt_me_reconnect_success_total 13280
telemt_me_reader_eof_total 14818
telemt_me_idle_close_by_peer_total 14817
telemt_me_route_drop_no_conn_total 276877
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 676838
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
telemt_me_writer_removed_unexpected_total 14604
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13275
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1324
telemt_user_connections_total{user="hello"} 676710
telemt_user_connections_current{user="hello"} 367
telemt_user_octets_from_client{user="hello"} 12289014476 (11.45 GB)
telemt_user_octets_to_client{user="hello"} 218794462036 (203.77 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 46
```