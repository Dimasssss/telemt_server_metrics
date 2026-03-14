# Server Metrics 2026-03-14 04:21:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 166998.2 (46h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4757111
telemt_connections_bad_total 39896
telemt_handshake_timeouts_total 109726
telemt_upstream_connect_attempt_total 35274
telemt_upstream_connect_success_total 35042
telemt_upstream_connect_fail_total 232
telemt_upstream_connect_attempts_per_request{bucket="1"} 35274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15800
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 232
telemt_me_keepalive_timeout_total 7296
telemt_me_reconnect_attempts_total 34538
telemt_me_reconnect_success_total 24395
telemt_me_reader_eof_total 26184
telemt_me_idle_close_by_peer_total 26183
telemt_me_route_drop_no_conn_total 1803955
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4363312
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16885
telemt_desync_full_logged_total 4553
telemt_desync_suppressed_total 12332
telemt_desync_frames_bucket_total{bucket="1_2"} 4214
telemt_desync_frames_bucket_total{bucket="3_10"} 6449
telemt_desync_frames_bucket_total{bucket="gt_10"} 6222
telemt_pool_swap_total 145
telemt_me_writer_removed_unexpected_total 25058
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 24382
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 663
telemt_user_connections_total{user="hello"} 4364886
telemt_user_connections_current{user="hello"} 765
telemt_user_octets_from_client{user="hello"} 63931565556 (59.54 GB)
telemt_user_octets_to_client{user="hello"} 1377449716221 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 66661.9 (18h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 731741
telemt_connections_bad_total 52498
telemt_handshake_timeouts_total 13409
telemt_upstream_connect_attempt_total 18396
telemt_upstream_connect_success_total 18136
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 18396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7831
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 221
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 2098
telemt_me_reconnect_attempts_total 16230
telemt_me_reconnect_success_total 12778
telemt_me_reader_eof_total 13566
telemt_me_idle_close_by_peer_total 13565
telemt_me_route_drop_no_conn_total 244164
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 584953
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1737
telemt_desync_full_logged_total 502
telemt_desync_suppressed_total 1235
telemt_desync_frames_bucket_total{bucket="1_2"} 366
telemt_desync_frames_bucket_total{bucket="3_10"} 769
telemt_desync_frames_bucket_total{bucket="gt_10"} 602
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 13062
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 12770
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 586904
telemt_user_connections_current{user="hello"} 280
telemt_user_octets_from_client{user="hello"} 6259955665 (5.83 GB)
telemt_user_octets_to_client{user="hello"} 194679280552 (181.31 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 196618.8 (54h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3427108
telemt_connections_bad_total 36987
telemt_handshake_timeouts_total 225687
telemt_upstream_connect_attempt_total 44471
telemt_upstream_connect_success_total 44450
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 44471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 236
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10602
telemt_me_reconnect_attempts_total 39320
telemt_me_reconnect_success_total 34352
telemt_me_reader_eof_total 36495
telemt_me_idle_close_by_peer_total 36494
telemt_me_route_drop_no_conn_total 1172191
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2854989
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9430
telemt_desync_full_logged_total 3152
telemt_desync_suppressed_total 6278
telemt_desync_frames_bucket_total{bucket="1_2"} 1637
telemt_desync_frames_bucket_total{bucket="3_10"} 3402
telemt_desync_frames_bucket_total{bucket="gt_10"} 4391
telemt_pool_swap_total 186
telemt_me_writer_removed_unexpected_total 34830
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 34311
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 478
telemt_user_connections_total{user="hello"} 2854204
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 45645753416 (42.51 GB)
telemt_user_octets_to_client{user="hello"} 1022768584153 (952.53 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 196621.3 (54h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2297971
telemt_connections_bad_total 23050
telemt_handshake_timeouts_total 257182
telemt_upstream_connect_attempt_total 61542
telemt_upstream_connect_success_total 59069
telemt_upstream_connect_fail_total 2336
telemt_upstream_connect_attempts_per_request{bucket="1"} 61268
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 166
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2335
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20456
telemt_me_reconnect_attempts_total 51297
telemt_me_reconnect_success_total 42259
telemt_me_reader_eof_total 45326
telemt_me_idle_close_by_peer_total 45319
telemt_me_route_drop_no_conn_total 780339
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1824541
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
telemt_me_writer_removed_unexpected_total 42906
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 42235
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 647
telemt_user_connections_total{user="hello"} 1830491
telemt_user_connections_current{user="hello"} 212
telemt_user_octets_from_client{user="hello"} 27755675283 (25.85 GB)
telemt_user_octets_to_client{user="hello"} 673555231622 (627.30 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 66054.9 (18h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727218
telemt_connections_bad_total 7975
telemt_handshake_timeouts_total 8732
telemt_upstream_connect_attempt_total 17102
telemt_upstream_connect_success_total 16645
telemt_upstream_connect_fail_total 457
telemt_upstream_connect_attempts_per_request{bucket="1"} 17102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8738
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 457
telemt_me_keepalive_timeout_total 1533
telemt_me_reconnect_attempts_total 52096
telemt_me_reconnect_success_total 13337
telemt_me_reader_eof_total 14884
telemt_me_idle_close_by_peer_total 14883
telemt_me_route_drop_no_conn_total 277608
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 678532
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1715
telemt_desync_full_logged_total 538
telemt_desync_suppressed_total 1177
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 665
telemt_desync_frames_bucket_total{bucket="gt_10"} 538
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 14662
telemt_me_refill_failed_total 1207
telemt_me_writer_restored_same_endpoint_total 13332
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 1325
telemt_user_connections_total{user="hello"} 678404
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 12322677700 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 219205867808 (204.15 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 42
```