# Server Metrics 2026-03-06 17:48:54 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 26816.8 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793534
telemt_connections_bad_total 13453
telemt_handshake_timeouts_total 3396
telemt_upstream_connect_attempt_total 13435
telemt_upstream_connect_success_total 13352
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 176
telemt_me_reconnect_attempts_total 2667
telemt_me_reconnect_success_total 2646
telemt_me_reader_eof_total 2773
telemt_me_idle_close_by_peer_total 2773
telemt_me_route_drop_no_conn_total 332898
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 4027
telemt_desync_full_logged_total 991
telemt_desync_suppressed_total 3036
telemt_desync_frames_bucket_total{bucket="1_2"} 947
telemt_desync_frames_bucket_total{bucket="3_10"} 1427
telemt_desync_frames_bucket_total{bucket="gt_10"} 1653
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2776
telemt_me_writer_restored_same_endpoint_total 2640
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 681625
telemt_user_connections_current{user="hello"} 1022
telemt_user_octets_from_client{user="hello"} 14008835824 (13.05 GB)
telemt_user_octets_to_client{user="hello"} 253502153532 (236.09 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 26816.8 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294811
telemt_connections_bad_total 1137
telemt_handshake_timeouts_total 8549
telemt_upstream_connect_attempt_total 12013
telemt_upstream_connect_success_total 11980
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 12013
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 984
telemt_me_reconnect_success_total 959
telemt_me_reader_eof_total 1012
telemt_me_idle_close_by_peer_total 1012
telemt_me_route_drop_no_conn_total 157761
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 941
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1013
telemt_me_writer_restored_same_endpoint_total 959
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 271591
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 3357786692 (3.13 GB)
telemt_user_octets_to_client{user="hello"} 107741535104 (100.34 GB)
telemt_user_unique_ips_current{user="hello"} 130
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 26816.6 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 573242
telemt_connections_bad_total 5572
telemt_handshake_timeouts_total 53131
telemt_upstream_connect_attempt_total 23085
telemt_upstream_connect_success_total 22975
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 23055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10267
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 344
telemt_me_reconnect_attempts_total 7970
telemt_me_reconnect_success_total 7939
telemt_me_reader_eof_total 8436
telemt_me_idle_close_by_peer_total 8436
telemt_me_route_drop_no_conn_total 301978
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1498
telemt_desync_full_logged_total 438
telemt_desync_suppressed_total 1060
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 561
telemt_desync_frames_bucket_total{bucket="gt_10"} 597
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8451
telemt_me_writer_restored_same_endpoint_total 7932
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 494910
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 7348655744 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 152464195804 (141.99 GB)
telemt_user_unique_ips_current{user="hello"} 170
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 26132.7 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559923
telemt_connections_bad_total 191448
telemt_handshake_timeouts_total 14651
telemt_upstream_connect_attempt_total 17977
telemt_upstream_connect_success_total 17975
telemt_upstream_connect_attempts_per_request{bucket="1"} 17975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7839
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 5139
telemt_me_reconnect_success_total 5114
telemt_me_reader_eof_total 5355
telemt_me_idle_close_by_peer_total 5355
telemt_me_route_drop_no_conn_total 180817
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 110
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 377
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 5
telemt_pool_force_close_total 269
telemt_me_writer_removed_unexpected_total 5361
telemt_me_writer_restored_same_endpoint_total 5113
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 315900
telemt_user_connections_current{user="hello"} 485
telemt_user_octets_from_client{user="hello"} 5113504036 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 111384715796 (103.74 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 26816.7 (7h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499988
telemt_connections_bad_total 11235
telemt_handshake_timeouts_total 5299
telemt_upstream_connect_attempt_total 11252
telemt_upstream_connect_success_total 11233
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11234
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 1795
telemt_me_reconnect_success_total 1775
telemt_me_reader_eof_total 1875
telemt_me_idle_close_by_peer_total 1874
telemt_me_route_drop_no_conn_total 230895
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 953
telemt_desync_full_logged_total 341
telemt_desync_suppressed_total 612
telemt_desync_frames_bucket_total{bucket="1_2"} 424
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1879
telemt_me_writer_restored_same_endpoint_total 1772
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 458109
telemt_user_connections_current{user="hello"} 561
telemt_user_octets_from_client{user="hello"} 20900388088 (19.47 GB)
telemt_user_octets_to_client{user="hello"} 215223113344 (200.44 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 91
```