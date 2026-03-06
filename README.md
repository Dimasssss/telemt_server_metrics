# Server Metrics 2026-03-06 12:50:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 8911.8 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279112
telemt_connections_bad_total 1648
telemt_handshake_timeouts_total 1514
telemt_upstream_connect_attempt_total 3053
telemt_upstream_connect_success_total 3026
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 3038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 30
telemt_me_reconnect_attempts_total 141
telemt_me_reconnect_success_total 137
telemt_me_reader_eof_total 140
telemt_me_idle_close_by_peer_total 140
telemt_me_route_drop_no_conn_total 82328
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1433
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 1092
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 512
telemt_desync_frames_bucket_total{bucket="gt_10"} 574
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 140
telemt_me_writer_restored_same_endpoint_total 131
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 219373
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 4296694160 (4.00 GB)
telemt_user_octets_to_client{user="hello"} 92294264364 (85.96 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 8911.6 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102402
telemt_connections_bad_total 764
telemt_handshake_timeouts_total 3765
telemt_upstream_connect_attempt_total 3934
telemt_upstream_connect_success_total 3924
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3934
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 528
telemt_me_reconnect_success_total 524
telemt_me_reader_eof_total 560
telemt_me_idle_close_by_peer_total 560
telemt_me_route_drop_no_conn_total 39152
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 330
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 145
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 91602
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 952250068 (908.14 MB)
telemt_user_octets_to_client{user="hello"} 41906436604 (39.03 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 8911.5 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202100
telemt_connections_bad_total 2610
telemt_handshake_timeouts_total 14107
telemt_upstream_connect_attempt_total 5342
telemt_upstream_connect_success_total 5313
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 1450
telemt_me_reader_eof_total 1520
telemt_me_idle_close_by_peer_total 1520
telemt_me_route_drop_no_conn_total 90293
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 263
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 317
telemt_me_writer_removed_unexpected_total 1521
telemt_me_writer_restored_same_endpoint_total 1445
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 178285
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 1903879876 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 57950943376 (53.97 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 8227.8 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110269
telemt_connections_bad_total 22493
telemt_handshake_timeouts_total 2341
telemt_upstream_connect_attempt_total 4590
telemt_upstream_connect_success_total 4590
telemt_upstream_connect_attempts_per_request{bucket="1"} 4590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1955
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 719
telemt_me_reconnect_success_total 714
telemt_me_reader_eof_total 725
telemt_me_idle_close_by_peer_total 725
telemt_me_route_drop_no_conn_total 37154
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 101
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 2
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 725
telemt_me_writer_restored_same_endpoint_total 714
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 83772
telemt_user_connections_current{user="hello"} 543
telemt_user_octets_from_client{user="hello"} 1141257800 (1.06 GB)
telemt_user_octets_to_client{user="hello"} 36177370216 (33.69 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 8912.0 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168328
telemt_connections_bad_total 4412
telemt_handshake_timeouts_total 2290
telemt_upstream_connect_attempt_total 2643
telemt_upstream_connect_success_total 2637
telemt_upstream_connect_attempts_per_request{bucket="1"} 2637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 103
telemt_me_reconnect_success_total 97
telemt_me_reader_eof_total 100
telemt_me_idle_close_by_peer_total 100
telemt_me_route_drop_no_conn_total 78148
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 254
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 168
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 101
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 151145
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 13551430492 (12.62 GB)
telemt_user_octets_to_client{user="hello"} 88721150128 (82.63 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 90
```