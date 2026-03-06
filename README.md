# Server Metrics 2026-03-06 13:00:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 9531.5 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297536
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 1610
telemt_upstream_connect_attempt_total 3380
telemt_upstream_connect_success_total 3352
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1455
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 177
telemt_me_reconnect_success_total 173
telemt_me_reader_eof_total 178
telemt_me_idle_close_by_peer_total 178
telemt_me_route_drop_no_conn_total 88726
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1529
telemt_desync_full_logged_total 372
telemt_desync_suppressed_total 1157
telemt_desync_frames_bucket_total{bucket="1_2"} 364
telemt_desync_frames_bucket_total{bucket="3_10"} 539
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 178
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 235340
telemt_user_connections_current{user="hello"} 1224
telemt_user_octets_from_client{user="hello"} 4541992184 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 97864920916 (91.14 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 199
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 9531.2 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110032
telemt_connections_bad_total 796
telemt_handshake_timeouts_total 3881
telemt_upstream_connect_attempt_total 4110
telemt_upstream_connect_success_total 4100
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 4110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1839
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 531
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 41951
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_restored_same_endpoint_total 526
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 98669
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 1014312692 (967.32 MB)
telemt_user_octets_to_client{user="hello"} 43976775664 (40.96 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 80
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 9531.1 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221246
telemt_connections_bad_total 3035
telemt_handshake_timeouts_total 14707
telemt_upstream_connect_attempt_total 5554
telemt_upstream_connect_success_total 5523
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 1457
telemt_me_reconnect_success_total 1453
telemt_me_reader_eof_total 1523
telemt_me_idle_close_by_peer_total 1523
telemt_me_route_drop_no_conn_total 100155
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 296
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 210
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 100
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 350
telemt_me_writer_removed_unexpected_total 1524
telemt_me_writer_restored_same_endpoint_total 1448
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 195639
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 2026809228 (1.89 GB)
telemt_user_octets_to_client{user="hello"} 60638038064 (56.47 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 8847.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120410
telemt_connections_bad_total 25453
telemt_handshake_timeouts_total 2507
telemt_upstream_connect_attempt_total 4674
telemt_upstream_connect_success_total 4674
telemt_upstream_connect_attempts_per_request{bucket="1"} 4674
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1994
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 721
telemt_me_reconnect_success_total 715
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 40442
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 175
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 113
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 65
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 90684
telemt_user_connections_current{user="hello"} 496
telemt_user_octets_from_client{user="hello"} 1192599436 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 37739163256 (35.15 GB)
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 9531.6 (2h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179057
telemt_connections_bad_total 5194
telemt_handshake_timeouts_total 2340
telemt_upstream_connect_attempt_total 2857
telemt_upstream_connect_success_total 2851
telemt_upstream_connect_attempts_per_request{bucket="1"} 2851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 110
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 109
telemt_me_idle_close_by_peer_total 109
telemt_me_route_drop_no_conn_total 82786
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 278
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 110
telemt_me_writer_restored_same_endpoint_total 103
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 160736
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 13644962508 (12.71 GB)
telemt_user_octets_to_client{user="hello"} 93643374944 (87.21 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 119
```