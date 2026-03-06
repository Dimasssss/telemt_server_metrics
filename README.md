# Server Metrics 2026-03-06 14:17:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 14149.0 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 422729
telemt_connections_bad_total 1840
telemt_handshake_timeouts_total 2286
telemt_upstream_connect_attempt_total 7628
telemt_upstream_connect_success_total 7580
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 1665
telemt_me_reconnect_success_total 1656
telemt_me_reader_eof_total 1739
telemt_me_idle_close_by_peer_total 1739
telemt_me_route_drop_no_conn_total 149128
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2338
telemt_desync_full_logged_total 562
telemt_desync_suppressed_total 1776
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 796
telemt_desync_frames_bucket_total{bucket="gt_10"} 992
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1741
telemt_me_writer_restored_same_endpoint_total 1650
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 356015
telemt_user_connections_current{user="hello"} 1173
telemt_user_octets_from_client{user="hello"} 10378511084 (9.67 GB)
telemt_user_octets_to_client{user="hello"} 147210961068 (137.10 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 14149.0 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160492
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 5163
telemt_upstream_connect_attempt_total 6136
telemt_upstream_connect_success_total 6119
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6135
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3254
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 599
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 630
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 79764
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 605
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_restored_same_endpoint_total 591
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 146613
telemt_user_connections_current{user="hello"} 555
telemt_user_octets_from_client{user="hello"} 1612704144 (1.50 GB)
telemt_user_octets_to_client{user="hello"} 68581866648 (63.87 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 14148.7 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 336149
telemt_connections_bad_total 5112
telemt_handshake_timeouts_total 35187
telemt_upstream_connect_attempt_total 10016
telemt_upstream_connect_success_total 9968
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 10009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5346
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 2823
telemt_me_reconnect_success_total 2811
telemt_me_reader_eof_total 2976
telemt_me_idle_close_by_peer_total 2976
telemt_me_route_drop_no_conn_total 158383
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 591
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 424
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 242
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 2977
telemt_me_writer_restored_same_endpoint_total 2806
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 284161
telemt_user_connections_current{user="hello"} 742
telemt_user_octets_from_client{user="hello"} 2980192668 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 90128189364 (83.94 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 13464.8 (3h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235967
telemt_connections_bad_total 43605
telemt_handshake_timeouts_total 7727
telemt_upstream_connect_attempt_total 6494
telemt_upstream_connect_success_total 6494
telemt_upstream_connect_attempts_per_request{bucket="1"} 6494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3780
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2714
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 847
telemt_me_reconnect_success_total 836
telemt_me_reader_eof_total 848
telemt_me_idle_close_by_peer_total 848
telemt_me_route_drop_no_conn_total 84663
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 251
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_restored_same_endpoint_total 836
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 151591
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 1792430568 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 58442877644 (54.43 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 14149.3 (3h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255071
telemt_connections_bad_total 7892
telemt_handshake_timeouts_total 2524
telemt_upstream_connect_attempt_total 6252
telemt_upstream_connect_success_total 6243
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 1056
telemt_me_reconnect_success_total 1045
telemt_me_reader_eof_total 1086
telemt_me_idle_close_by_peer_total 1085
telemt_me_route_drop_no_conn_total 135409
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 419
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1089
telemt_me_writer_restored_same_endpoint_total 1044
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 232197
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 14151396320 (13.18 GB)
telemt_user_octets_to_client{user="hello"} 133023530048 (123.89 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 98
```