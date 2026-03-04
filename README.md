# Server Metrics 2026-03-04 13:55:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 60321.7 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1090110
telemt_connections_bad_total 13917
telemt_handshake_timeouts_total 18786
telemt_upstream_connect_attempt_total 35986
telemt_upstream_connect_success_total 35824
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 35824
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 402
telemt_me_reconnect_attempts_total 7724
telemt_me_reconnect_success_total 7667
telemt_me_reader_eof_total 7913
telemt_me_idle_close_by_peer_total 7912
telemt_me_route_drop_no_conn_total 395769
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 236
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1874
telemt_desync_full_logged_total 621
telemt_desync_suppressed_total 1253
telemt_desync_frames_bucket_total{bucket="1_2"} 536
telemt_desync_frames_bucket_total{bucket="3_10"} 714
telemt_desync_frames_bucket_total{bucket="gt_10"} 624
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7913
telemt_me_writer_restored_same_endpoint_total 7645
telemt_me_writer_removed_unexpected_minus_restored_total 268
telemt_user_connections_total{user="hello"} 863180
telemt_user_connections_current{user="hello"} 1185
telemt_user_octets_from_client{user="hello"} 9836609164 (9.16 GB)
telemt_user_octets_to_client{user="hello"} 290881192160 (270.90 GB)
telemt_user_unique_ips_current{user="hello"} 106
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 60318.1 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 420226
telemt_connections_bad_total 3564
telemt_handshake_timeouts_total 29290
telemt_upstream_connect_attempt_total 108049
telemt_upstream_connect_success_total 106435
telemt_upstream_connect_fail_total 769
telemt_upstream_connect_attempts_per_request{bucket="1"} 106429
telemt_upstream_connect_attempts_per_request{bucket="2"} 775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 70034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 769
telemt_me_keepalive_timeout_total 1463
telemt_me_reconnect_attempts_total 59274
telemt_me_reconnect_success_total 59180
telemt_me_reader_eof_total 60712
telemt_me_idle_close_by_peer_total 60711
telemt_me_route_drop_no_conn_total 170044
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 252
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 815
telemt_desync_full_logged_total 255
telemt_desync_suppressed_total 560
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 60792
telemt_me_writer_restored_same_endpoint_total 59155
telemt_me_writer_removed_unexpected_minus_restored_total 1637
telemt_user_connections_total{user="hello"} 325267
telemt_user_connections_current{user="hello"} 419
telemt_user_octets_from_client{user="hello"} 4174510012 (3.89 GB)
telemt_user_octets_to_client{user="hello"} 103277316668 (96.18 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 60317.0 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 824427
telemt_connections_bad_total 179258
telemt_handshake_timeouts_total 29139
telemt_upstream_connect_attempt_total 83176
telemt_upstream_connect_success_total 82659
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 82658
telemt_upstream_connect_attempts_per_request{bucket="2"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33635
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1087
telemt_me_reconnect_attempts_total 37951
telemt_me_reconnect_success_total 37852
telemt_me_reader_eof_total 39846
telemt_me_idle_close_by_peer_total 39842
telemt_me_route_drop_no_conn_total 301450
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1684
telemt_desync_full_logged_total 569
telemt_desync_suppressed_total 1115
telemt_desync_frames_bucket_total{bucket="1_2"} 547
telemt_desync_frames_bucket_total{bucket="3_10"} 538
telemt_desync_frames_bucket_total{bucket="gt_10"} 599
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39858
telemt_me_writer_restored_same_endpoint_total 37830
telemt_me_writer_removed_unexpected_minus_restored_total 2028
telemt_user_connections_total{user="hello"} 578526
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 12307064788 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 196266983520 (182.79 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 6994.3 (1h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85976
telemt_connections_bad_total 8617
telemt_handshake_timeouts_total 1578
telemt_upstream_connect_attempt_total 3191
telemt_upstream_connect_success_total 3191
telemt_upstream_connect_attempts_per_request{bucket="1"} 3191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1226
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 429
telemt_me_reconnect_success_total 444
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 30332
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 102
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 436
telemt_me_writer_restored_same_endpoint_total 423
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 74517
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 1259324516 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 46711225112 (43.50 GB)
telemt_user_unique_ips_current{user="hello"} 63
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 7353.5 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128987
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 2181
telemt_upstream_connect_attempt_total 4834
telemt_upstream_connect_success_total 4814
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4814
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1203
telemt_me_reconnect_success_total 1214
telemt_me_reader_eof_total 1237
telemt_me_idle_close_by_peer_total 1237
telemt_me_route_drop_no_conn_total 44675
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 216
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 142
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1237
telemt_me_writer_restored_same_endpoint_total 1194
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 111054
telemt_user_connections_current{user="hello"} 574
telemt_user_octets_from_client{user="hello"} 1285755724 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 31013119156 (28.88 GB)
telemt_user_unique_ips_current{user="hello"} 48
```