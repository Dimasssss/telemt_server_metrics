# Server Metrics 2026-03-06 15:45:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 19419.5 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 580741
telemt_connections_bad_total 6104
telemt_handshake_timeouts_total 2916
telemt_upstream_connect_attempt_total 9777
telemt_upstream_connect_success_total 9718
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5139
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4518
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 1969
telemt_me_reconnect_success_total 1956
telemt_me_reader_eof_total 2054
telemt_me_idle_close_by_peer_total 2054
telemt_me_route_drop_no_conn_total 218881
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3081
telemt_desync_full_logged_total 748
telemt_desync_suppressed_total 2333
telemt_desync_frames_bucket_total{bucket="1_2"} 740
telemt_desync_frames_bucket_total{bucket="3_10"} 1054
telemt_desync_frames_bucket_total{bucket="gt_10"} 1287
telemt_pool_swap_total 4
telemt_pool_force_close_total 233
telemt_me_writer_removed_unexpected_total 2056
telemt_me_writer_restored_same_endpoint_total 1950
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 495984
telemt_user_connections_current{user="hello"} 1286
telemt_user_octets_from_client{user="hello"} 12000762460 (11.18 GB)
telemt_user_octets_to_client{user="hello"} 190175197756 (177.11 GB)
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 19419.3 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219243
telemt_connections_bad_total 861
telemt_handshake_timeouts_total 6661
telemt_upstream_connect_attempt_total 9075
telemt_upstream_connect_success_total 9054
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 9075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4722
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 915
telemt_me_reconnect_success_total 900
telemt_me_reader_eof_total 950
telemt_me_idle_close_by_peer_total 950
telemt_me_route_drop_no_conn_total 109153
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 763
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 515
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 285
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 950
telemt_me_writer_restored_same_endpoint_total 900
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 202401
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 2273250364 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 84083544864 (78.31 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 19419.1 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 437058
telemt_connections_bad_total 5359
telemt_handshake_timeouts_total 39617
telemt_upstream_connect_attempt_total 15974
telemt_upstream_connect_success_total 15899
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 15962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 5354
telemt_me_reconnect_success_total 5332
telemt_me_reader_eof_total 5647
telemt_me_idle_close_by_peer_total 5647
telemt_me_route_drop_no_conn_total 208779
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 862
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 205
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5651
telemt_me_writer_restored_same_endpoint_total 5327
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 378157
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 5692072660 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 120730878764 (112.44 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 18735.4 (5h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 351075
telemt_connections_bad_total 87728
telemt_handshake_timeouts_total 10390
telemt_upstream_connect_attempt_total 9967
telemt_upstream_connect_success_total 9966
telemt_upstream_connect_attempts_per_request{bucket="1"} 9966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3997
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 1943
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1966
telemt_me_idle_close_by_peer_total 1966
telemt_me_route_drop_no_conn_total 112443
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 292
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 101
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1966
telemt_me_writer_restored_same_endpoint_total 1927
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 218340
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 2558236688 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 79699596332 (74.23 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 19419.5 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342789
telemt_connections_bad_total 10808
telemt_handshake_timeouts_total 2765
telemt_upstream_connect_attempt_total 9388
telemt_upstream_connect_success_total 9376
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4239
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 154
telemt_me_reconnect_attempts_total 1761
telemt_me_reconnect_success_total 1746
telemt_me_reader_eof_total 1841
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 175505
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 631
telemt_desync_full_logged_total 223
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 5
telemt_pool_force_close_total 221
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1845
telemt_me_writer_restored_same_endpoint_total 1744
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 314693
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 14944818064 (13.92 GB)
telemt_user_octets_to_client{user="hello"} 168544766428 (156.97 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 141
```