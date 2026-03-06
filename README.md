# Server Metrics 2026-03-06 17:43:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 26509.5 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786239
telemt_connections_bad_total 13386
telemt_handshake_timeouts_total 3367
telemt_upstream_connect_attempt_total 13342
telemt_upstream_connect_success_total 13259
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13293
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6009
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 2667
telemt_me_reconnect_success_total 2646
telemt_me_reader_eof_total 2773
telemt_me_idle_close_by_peer_total 2773
telemt_me_route_drop_no_conn_total 329654
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 4015
telemt_desync_full_logged_total 985
telemt_desync_suppressed_total 3030
telemt_desync_frames_bucket_total{bucket="1_2"} 942
telemt_desync_frames_bucket_total{bucket="3_10"} 1423
telemt_desync_frames_bucket_total{bucket="gt_10"} 1650
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2776
telemt_me_writer_restored_same_endpoint_total 2640
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 675018
telemt_user_connections_current{user="hello"} 1049
telemt_user_octets_from_client{user="hello"} 13954969332 (13.00 GB)
telemt_user_octets_to_client{user="hello"} 250505676980 (233.30 GB)
telemt_user_unique_ips_current{user="hello"} 273
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 26509.5 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291832
telemt_connections_bad_total 1137
telemt_handshake_timeouts_total 8469
telemt_upstream_connect_attempt_total 11885
telemt_upstream_connect_success_total 11852
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5687
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 978
telemt_me_reconnect_success_total 954
telemt_me_reader_eof_total 1007
telemt_me_idle_close_by_peer_total 1007
telemt_me_route_drop_no_conn_total 156623
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 933
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1008
telemt_me_writer_restored_same_endpoint_total 954
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 268846
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 3311978328 (3.08 GB)
telemt_user_octets_to_client{user="hello"} 106625093448 (99.30 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 26509.4 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568206
telemt_connections_bad_total 5554
telemt_handshake_timeouts_total 52910
telemt_upstream_connect_attempt_total 22978
telemt_upstream_connect_success_total 22868
telemt_upstream_connect_fail_total 80
telemt_upstream_connect_attempts_per_request{bucket="1"} 22948
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10225
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 80
telemt_me_keepalive_timeout_total 342
telemt_me_reconnect_attempts_total 7968
telemt_me_reconnect_success_total 7937
telemt_me_reader_eof_total 8433
telemt_me_idle_close_by_peer_total 8433
telemt_me_route_drop_no_conn_total 299875
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1460
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 1032
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 545
telemt_desync_frames_bucket_total{bucket="gt_10"} 583
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8448
telemt_me_writer_restored_same_endpoint_total 7930
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 490540
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 7301301004 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 151448859088 (141.05 GB)
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 25825.5 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 555598
telemt_connections_bad_total 191123
telemt_handshake_timeouts_total 14114
telemt_upstream_connect_attempt_total 17923
telemt_upstream_connect_success_total 17921
telemt_upstream_connect_attempts_per_request{bucket="1"} 17921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10107
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7814
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 5138
telemt_me_reconnect_success_total 5113
telemt_me_reader_eof_total 5354
telemt_me_idle_close_by_peer_total 5354
telemt_me_route_drop_no_conn_total 179203
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 109
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
telemt_me_writer_removed_unexpected_total 5360
telemt_me_writer_restored_same_endpoint_total 5112
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 312521
telemt_user_connections_current{user="hello"} 518
telemt_user_octets_from_client{user="hello"} 5097702628 (4.75 GB)
telemt_user_octets_to_client{user="hello"} 109847338388 (102.30 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 26509.8 (7h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493790
telemt_connections_bad_total 11144
telemt_handshake_timeouts_total 5214
telemt_upstream_connect_attempt_total 11148
telemt_upstream_connect_success_total 11131
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11132
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5991
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5071
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 183
telemt_me_reconnect_attempts_total 1793
telemt_me_reconnect_success_total 1772
telemt_me_reader_eof_total 1873
telemt_me_idle_close_by_peer_total 1872
telemt_me_route_drop_no_conn_total 228740
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 934
telemt_desync_full_logged_total 333
telemt_desync_suppressed_total 601
telemt_desync_frames_bucket_total{bucket="1_2"} 415
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1877
telemt_me_writer_restored_same_endpoint_total 1769
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 452631
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 20823871844 (19.39 GB)
telemt_user_octets_to_client{user="hello"} 213342450956 (198.69 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 98
```