# Server Metrics 2026-03-06 15:30:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 18497.4 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 549676
telemt_connections_bad_total 5156
telemt_handshake_timeouts_total 2834
telemt_upstream_connect_attempt_total 9449
telemt_upstream_connect_success_total 9391
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4365
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 1911
telemt_me_reconnect_success_total 1899
telemt_me_reader_eof_total 1996
telemt_me_idle_close_by_peer_total 1996
telemt_me_route_drop_no_conn_total 197251
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2916
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 2195
telemt_desync_frames_bucket_total{bucket="1_2"} 701
telemt_desync_frames_bucket_total{bucket="3_10"} 986
telemt_desync_frames_bucket_total{bucket="gt_10"} 1229
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1998
telemt_me_writer_restored_same_endpoint_total 1893
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 469035
telemt_user_connections_current{user="hello"} 1072
telemt_user_octets_from_client{user="hello"} 11788360812 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 185307990528 (172.58 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 18497.2 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 209446
telemt_connections_bad_total 860
telemt_handshake_timeouts_total 6593
telemt_upstream_connect_attempt_total 8873
telemt_upstream_connect_success_total 8853
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4240
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4612
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 914
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 949
telemt_me_idle_close_by_peer_total 949
telemt_me_route_drop_no_conn_total 103661
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 742
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 504
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 336
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 949
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 192876
telemt_user_connections_current{user="hello"} 521
telemt_user_octets_from_client{user="hello"} 2148238348 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 82028943928 (76.40 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 18497.1 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 418039
telemt_connections_bad_total 5296
telemt_handshake_timeouts_total 37763
telemt_upstream_connect_attempt_total 15538
telemt_upstream_connect_success_total 15466
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 15525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 212
telemt_me_reconnect_attempts_total 5332
telemt_me_reconnect_success_total 5312
telemt_me_reader_eof_total 5627
telemt_me_idle_close_by_peer_total 5627
telemt_me_route_drop_no_conn_total 198482
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 779
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 188
telemt_desync_frames_bucket_total{bucket="3_10"} 315
telemt_desync_frames_bucket_total{bucket="gt_10"} 276
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5631
telemt_me_writer_restored_same_endpoint_total 5307
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 361661
telemt_user_connections_current{user="hello"} 732
telemt_user_octets_from_client{user="hello"} 5534389276 (5.15 GB)
telemt_user_octets_to_client{user="hello"} 114849278988 (106.96 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 17813.3 (4h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324158
telemt_connections_bad_total 73606
telemt_handshake_timeouts_total 10310
telemt_upstream_connect_attempt_total 9573
telemt_upstream_connect_success_total 9571
telemt_upstream_connect_attempts_per_request{bucket="1"} 9571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3808
telemt_me_keepalive_timeout_total 114
telemt_me_reconnect_attempts_total 1931
telemt_me_reconnect_success_total 1916
telemt_me_reader_eof_total 1951
telemt_me_idle_close_by_peer_total 1951
telemt_me_route_drop_no_conn_total 106021
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 75
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 283
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1951
telemt_me_writer_restored_same_endpoint_total 1916
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 205932
telemt_user_connections_current{user="hello"} 578
telemt_user_octets_from_client{user="hello"} 2438381596 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 76101277288 (70.87 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 18497.6 (5h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326948
telemt_connections_bad_total 9801
telemt_handshake_timeouts_total 2740
telemt_upstream_connect_attempt_total 9018
telemt_upstream_connect_success_total 9005
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4095
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 1734
telemt_me_reconnect_success_total 1718
telemt_me_reader_eof_total 1814
telemt_me_idle_close_by_peer_total 1813
telemt_me_route_drop_no_conn_total 169262
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 574
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 266
telemt_desync_frames_bucket_total{bucket="3_10"} 160
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1818
telemt_me_writer_restored_same_endpoint_total 1717
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 300336
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 14832695828 (13.81 GB)
telemt_user_octets_to_client{user="hello"} 162862010832 (151.68 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 88
```