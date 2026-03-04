# Server Metrics 2026-03-04 11:42:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 52323.6 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 852450
telemt_connections_bad_total 12055
telemt_handshake_timeouts_total 11868
telemt_upstream_connect_attempt_total 32439
telemt_upstream_connect_success_total 32302
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 32302
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14393
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 361
telemt_me_reconnect_attempts_total 7084
telemt_me_reconnect_success_total 7037
telemt_me_reader_eof_total 7257
telemt_me_idle_close_by_peer_total 7257
telemt_me_route_drop_no_conn_total 323661
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1376
telemt_desync_full_logged_total 468
telemt_desync_suppressed_total 908
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 536
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 14
telemt_pool_force_close_total 524
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7257
telemt_me_writer_restored_same_endpoint_total 7016
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 684193
telemt_user_connections_current{user="hello"} 930
telemt_user_octets_from_client{user="hello"} 7413518796 (6.90 GB)
telemt_user_octets_to_client{user="hello"} 208197200832 (193.90 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 52320.0 (14h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339229
telemt_connections_bad_total 3027
telemt_handshake_timeouts_total 27381
telemt_upstream_connect_attempt_total 100801
telemt_upstream_connect_success_total 99278
telemt_upstream_connect_fail_total 723
telemt_upstream_connect_attempts_per_request{bucket="1"} 99272
telemt_upstream_connect_attempts_per_request{bucket="2"} 729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32810
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 723
telemt_me_keepalive_timeout_total 1396
telemt_me_reconnect_attempts_total 56896
telemt_me_reconnect_success_total 56809
telemt_me_reader_eof_total 58244
telemt_me_idle_close_by_peer_total 58243
telemt_me_route_drop_no_conn_total 142607
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 623
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 406
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58324
telemt_me_writer_restored_same_endpoint_total 56784
telemt_me_writer_removed_unexpected_minus_restored_total 1540
telemt_user_connections_total{user="hello"} 256160
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 3324264048 (3.10 GB)
telemt_user_octets_to_client{user="hello"} 81322479528 (75.74 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 52318.8 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 647445
telemt_connections_bad_total 156924
telemt_handshake_timeouts_total 20518
telemt_upstream_connect_attempt_total 78481
telemt_upstream_connect_success_total 78030
telemt_upstream_connect_fail_total 215
telemt_upstream_connect_attempts_per_request{bucket="1"} 78029
telemt_upstream_connect_attempts_per_request{bucket="2"} 216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32073
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 216
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 215
telemt_me_keepalive_timeout_total 1025
telemt_me_reconnect_attempts_total 36932
telemt_me_reconnect_success_total 36842
telemt_me_reader_eof_total 38812
telemt_me_idle_close_by_peer_total 38808
telemt_me_route_drop_no_conn_total 243285
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1139
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 733
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38824
telemt_me_writer_restored_same_endpoint_total 36820
telemt_me_writer_removed_unexpected_minus_restored_total 2004
telemt_user_connections_total{user="hello"} 450553
telemt_user_connections_current{user="hello"} 514
telemt_user_octets_from_client{user="hello"} 5901442604 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 149944429220 (139.65 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 52317.8 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418974
telemt_connections_bad_total 29211
telemt_handshake_timeouts_total 66686
telemt_upstream_connect_attempt_total 38558
telemt_upstream_connect_success_total 38403
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 38403
telemt_upstream_connect_attempts_per_request{bucket="2"} 76
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 433
telemt_me_reconnect_attempts_total 8222
telemt_me_reconnect_success_total 8193
telemt_me_reader_eof_total 8376
telemt_me_idle_close_by_peer_total 8376
telemt_me_route_drop_no_conn_total 119923
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 214
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 234
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 80
telemt_pool_swap_total 14
telemt_pool_force_close_total 375
telemt_me_writer_removed_unexpected_total 8376
telemt_me_writer_restored_same_endpoint_total 8172
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 300662
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 3672276948 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 111405707700 (103.75 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 52316.5 (14h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 565788
telemt_connections_bad_total 6819
telemt_handshake_timeouts_total 132473
telemt_upstream_connect_attempt_total 74378
telemt_upstream_connect_success_total 73869
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 73869
telemt_upstream_connect_attempts_per_request{bucket="2"} 241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44461
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 200
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_timeout_total 970
telemt_me_reconnect_attempts_total 35742
telemt_me_reconnect_success_total 35707
telemt_me_reader_eof_total 37452
telemt_me_idle_close_by_peer_total 37451
telemt_me_route_drop_no_conn_total 181895
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 221
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 820
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 562
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 330
telemt_pool_swap_total 6
telemt_pool_force_close_total 263
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 37464
telemt_me_writer_restored_same_endpoint_total 35682
telemt_me_writer_removed_unexpected_minus_restored_total 1782
telemt_user_connections_total{user="hello"} 401424
telemt_user_connections_current{user="hello"} 593
telemt_user_octets_from_client{user="hello"} 5186661000 (4.83 GB)
telemt_user_octets_to_client{user="hello"} 110455736468 (102.87 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 50
```