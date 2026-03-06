# Server Metrics 2026-03-06 11:33:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 4290.7 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149958
telemt_connections_bad_total 338
telemt_handshake_timeouts_total 843
telemt_upstream_connect_attempt_total 1235
telemt_upstream_connect_success_total 1223
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1228
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 24
telemt_me_reconnect_success_total 26
telemt_me_reader_eof_total 22
telemt_me_idle_close_by_peer_total 22
telemt_me_route_drop_no_conn_total 34855
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 509
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 1
telemt_pool_force_close_total 32
telemt_me_writer_removed_unexpected_total 22
telemt_me_writer_restored_same_endpoint_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 103180
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 2961772916 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 36848230656 (34.32 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 4290.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46517
telemt_connections_bad_total 138
telemt_handshake_timeouts_total 1398
telemt_upstream_connect_attempt_total 1320
telemt_upstream_connect_success_total 1317
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 693
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 22
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 23
telemt_me_idle_close_by_peer_total 23
telemt_me_route_drop_no_conn_total 17138
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 169
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 1
telemt_pool_force_close_total 29
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_restored_same_endpoint_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 41548
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 442766360 (422.25 MB)
telemt_user_octets_to_client{user="hello"} 16059511568 (14.96 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 4290.5 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81414
telemt_connections_bad_total 481
telemt_handshake_timeouts_total 4981
telemt_upstream_connect_attempt_total 1898
telemt_upstream_connect_success_total 1887
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 1896
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 804
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 210
telemt_me_reconnect_success_total 210
telemt_me_reader_eof_total 218
telemt_me_idle_close_by_peer_total 218
telemt_me_route_drop_no_conn_total 31198
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 146
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 56
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_writer_removed_unexpected_total 218
telemt_me_writer_restored_same_endpoint_total 205
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 74098
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 838059072 (799.24 MB)
telemt_user_octets_to_client{user="hello"} 21654231424 (20.17 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 3606.5 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40061
telemt_connections_bad_total 3223
telemt_handshake_timeouts_total 973
telemt_upstream_connect_attempt_total 2077
telemt_upstream_connect_success_total 2077
telemt_upstream_connect_attempts_per_request{bucket="1"} 2077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 843
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 353
telemt_me_reconnect_success_total 351
telemt_me_reader_eof_total 356
telemt_me_idle_close_by_peer_total 356
telemt_me_route_drop_no_conn_total 14514
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 56
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_me_writer_removed_unexpected_total 356
telemt_me_writer_restored_same_endpoint_total 351
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 35042
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 378804288 (361.26 MB)
telemt_user_octets_to_client{user="hello"} 9940432400 (9.26 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 4290.8 (1h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84067
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 1739
telemt_upstream_connect_attempt_total 1066
telemt_upstream_connect_success_total 1065
telemt_upstream_connect_attempts_per_request{bucket="1"} 1065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 542
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 12
telemt_me_reconnect_success_total 10
telemt_me_reader_eof_total 11
telemt_me_idle_close_by_peer_total 11
telemt_me_route_drop_no_conn_total 26939
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 135
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 34
telemt_pool_swap_total 1
telemt_pool_force_close_total 20
telemt_me_writer_removed_unexpected_total 11
telemt_me_writer_restored_same_endpoint_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 76567
telemt_user_connections_current{user="hello"} 585
telemt_user_octets_from_client{user="hello"} 11227336948 (10.46 GB)
telemt_user_octets_to_client{user="hello"} 36275247588 (33.78 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 106
```