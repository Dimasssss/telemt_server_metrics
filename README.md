# Server Metrics 2026-03-06 12:24:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 7369.1 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 237680
telemt_connections_bad_total 699
telemt_handshake_timeouts_total 1337
telemt_upstream_connect_attempt_total 2386
telemt_upstream_connect_success_total 2364
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 101
telemt_me_reader_eof_total 103
telemt_me_idle_close_by_peer_total 103
telemt_me_route_drop_no_conn_total 66357
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1150
telemt_desync_full_logged_total 273
telemt_desync_suppressed_total 877
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 103
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 180099
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 3917400356 (3.65 GB)
telemt_user_octets_to_client{user="hello"} 76897163080 (71.62 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 7368.9 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80408
telemt_connections_bad_total 419
telemt_handshake_timeouts_total 3203
telemt_upstream_connect_attempt_total 3834
telemt_upstream_connect_success_total 3825
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 3834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2091
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 525
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 31396
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 262
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 109
telemt_pool_swap_total 2
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 71780
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 717680796 (684.43 MB)
telemt_user_octets_to_client{user="hello"} 34534395004 (32.16 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 7368.8 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148315
telemt_connections_bad_total 1323
telemt_handshake_timeouts_total 11883
telemt_upstream_connect_attempt_total 5151
telemt_upstream_connect_success_total 5131
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 69989
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 242
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 59
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 1
telemt_pool_force_close_total 1
telemt_pool_stale_pick_total 17
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1443
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 131565
telemt_user_connections_current{user="hello"} 778
telemt_user_octets_from_client{user="hello"} 1439202720 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 48893685700 (45.54 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 6684.8 (1h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81262
telemt_connections_bad_total 11432
telemt_handshake_timeouts_total 1796
telemt_upstream_connect_attempt_total 3394
telemt_upstream_connect_success_total 3394
telemt_upstream_connect_attempts_per_request{bucket="1"} 3394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1444
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 440
telemt_me_reconnect_success_total 437
telemt_me_reader_eof_total 443
telemt_me_idle_close_by_peer_total 443
telemt_me_route_drop_no_conn_total 28691
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 111
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 443
telemt_me_writer_restored_same_endpoint_total 437
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 66699
telemt_user_connections_current{user="hello"} 433
telemt_user_octets_from_client{user="hello"} 735108188 (701.05 MB)
telemt_user_octets_to_client{user="hello"} 29549089500 (27.52 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 7369.1 (2h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 142523
telemt_connections_bad_total 2266
telemt_handshake_timeouts_total 2155
telemt_upstream_connect_attempt_total 2085
telemt_upstream_connect_success_total 2081
telemt_upstream_connect_attempts_per_request{bucket="1"} 2081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 29
telemt_me_reconnect_attempts_total 44
telemt_me_reconnect_success_total 38
telemt_me_reader_eof_total 40
telemt_me_idle_close_by_peer_total 40
telemt_me_route_drop_no_conn_total 65064
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 30
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 80
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_pool_swap_total 2
telemt_pool_force_close_total 58
telemt_pool_stale_pick_total 141
telemt_me_writer_removed_unexpected_total 41
telemt_me_writer_restored_same_endpoint_total 38
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 128359
telemt_user_connections_current{user="hello"} 723
telemt_user_octets_from_client{user="hello"} 13098468032 (12.20 GB)
telemt_user_octets_to_client{user="hello"} 71217132232 (66.33 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 104
```