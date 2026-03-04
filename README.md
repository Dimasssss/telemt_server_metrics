# Server Metrics 2026-03-04 10:00:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 46178.9 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654627
telemt_connections_bad_total 10946
telemt_handshake_timeouts_total 7414
telemt_upstream_connect_attempt_total 30837
telemt_upstream_connect_success_total 30709
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30709
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13649
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 328
telemt_me_reconnect_attempts_total 7044
telemt_me_reconnect_success_total 7000
telemt_me_reader_eof_total 7219
telemt_me_idle_close_by_peer_total 7219
telemt_me_route_drop_no_conn_total 233096
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 185
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1104
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 310
telemt_desync_frames_bucket_total{bucket="3_10"} 419
telemt_desync_frames_bucket_total{bucket="gt_10"} 375
telemt_pool_swap_total 10
telemt_pool_force_close_total 430
telemt_me_writer_removed_unexpected_total 7219
telemt_me_writer_restored_same_endpoint_total 6979
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 537732
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 5972008972 (5.56 GB)
telemt_user_octets_to_client{user="hello"} 158263837384 (147.39 GB)
telemt_user_unique_ips_current{user="hello"} 149
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 46168.9 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262877
telemt_connections_bad_total 2253
telemt_handshake_timeouts_total 26076
telemt_upstream_connect_attempt_total 93760
telemt_upstream_connect_success_total 92443
telemt_upstream_connect_fail_total 620
telemt_upstream_connect_attempts_per_request{bucket="1"} 92437
telemt_upstream_connect_attempts_per_request{bucket="2"} 626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30337
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 620
telemt_me_keepalive_timeout_total 1343
telemt_me_reconnect_attempts_total 54316
telemt_me_reconnect_success_total 54234
telemt_me_reader_eof_total 55632
telemt_me_idle_close_by_peer_total 55631
telemt_me_route_drop_no_conn_total 120698
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 525
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55712
telemt_me_writer_restored_same_endpoint_total 54209
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 200914
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 2417548860 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 67077527868 (62.47 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 46167.8 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528442
telemt_connections_bad_total 141006
telemt_handshake_timeouts_total 15924
telemt_upstream_connect_attempt_total 66563
telemt_upstream_connect_success_total 66143
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 66142
telemt_upstream_connect_attempts_per_request{bucket="2"} 201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 880
telemt_me_reconnect_attempts_total 30103
telemt_me_reconnect_success_total 30022
telemt_me_reader_eof_total 31645
telemt_me_idle_close_by_peer_total 31642
telemt_me_route_drop_no_conn_total 179408
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 194
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 856
telemt_desync_full_logged_total 314
telemt_desync_suppressed_total 542
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 293
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 31656
telemt_me_writer_restored_same_endpoint_total 30001
telemt_me_writer_removed_unexpected_minus_restored_total 1655
telemt_user_connections_total{user="hello"} 355133
telemt_user_connections_current{user="hello"} 694
telemt_user_octets_from_client{user="hello"} 3816822404 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 125791915344 (117.15 GB)
telemt_user_unique_ips_current{user="hello"} 66
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 46166.7 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 339713
telemt_connections_bad_total 23671
telemt_handshake_timeouts_total 53456
telemt_upstream_connect_attempt_total 33163
telemt_upstream_connect_success_total 33024
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 33024
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 377
telemt_me_reconnect_attempts_total 6624
telemt_me_reconnect_success_total 6602
telemt_me_reader_eof_total 6729
telemt_me_idle_close_by_peer_total 6729
telemt_me_route_drop_no_conn_total 96481
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 179
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6729
telemt_me_writer_restored_same_endpoint_total 6581
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 241252
telemt_user_connections_current{user="hello"} 418
telemt_user_octets_from_client{user="hello"} 2649731800 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 84421346744 (78.62 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 46165.5 (12h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471966
telemt_connections_bad_total 6489
telemt_handshake_timeouts_total 132172
telemt_upstream_connect_attempt_total 68312
telemt_upstream_connect_success_total 67872
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 67872
telemt_upstream_connect_attempts_per_request{bucket="2"} 207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_keepalive_timeout_total 898
telemt_me_reconnect_attempts_total 33514
telemt_me_reconnect_success_total 33484
telemt_me_reader_eof_total 35162
telemt_me_idle_close_by_peer_total 35161
telemt_me_route_drop_no_conn_total 145138
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 476
telemt_desync_full_logged_total 149
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35174
telemt_me_writer_restored_same_endpoint_total 33459
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 313246
telemt_user_connections_current{user="hello"} 538
telemt_user_octets_from_client{user="hello"} 4342331628 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 78576958324 (73.18 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 48
```