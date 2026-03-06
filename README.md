# Server Metrics 2026-03-06 16:36:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 22497.3 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674232
telemt_connections_bad_total 10551
telemt_handshake_timeouts_total 3097
telemt_upstream_connect_attempt_total 10930
telemt_upstream_connect_success_total 10863
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 10891
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5767
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 2029
telemt_me_reconnect_success_total 2013
telemt_me_reader_eof_total 2113
telemt_me_idle_close_by_peer_total 2113
telemt_me_route_drop_no_conn_total 289636
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3461
telemt_desync_full_logged_total 829
telemt_desync_suppressed_total 2632
telemt_desync_frames_bucket_total{bucket="1_2"} 831
telemt_desync_frames_bucket_total{bucket="3_10"} 1197
telemt_desync_frames_bucket_total{bucket="gt_10"} 1433
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2115
telemt_me_writer_restored_same_endpoint_total 2007
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 581446
telemt_user_connections_current{user="hello"} 1182
telemt_user_octets_from_client{user="hello"} 13066052288 (12.17 GB)
telemt_user_octets_to_client{user="hello"} 216092054764 (201.25 GB)
telemt_user_unique_ips_current{user="hello"} 310
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 22497.3 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254708
telemt_connections_bad_total 896
telemt_handshake_timeouts_total 7475
telemt_upstream_connect_attempt_total 10449
telemt_upstream_connect_success_total 10424
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 10449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5422
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 955
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 987
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 144112
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 558
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 234088
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 2700176452 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 94864500668 (88.35 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 22497.1 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 504003
telemt_connections_bad_total 5426
telemt_handshake_timeouts_total 51470
telemt_upstream_connect_attempt_total 18805
telemt_upstream_connect_success_total 18725
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 18792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10373
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 254
telemt_me_reconnect_attempts_total 6347
telemt_me_reconnect_success_total 6321
telemt_me_reader_eof_total 6686
telemt_me_idle_close_by_peer_total 6686
telemt_me_route_drop_no_conn_total 257221
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1089
telemt_desync_full_logged_total 327
telemt_desync_suppressed_total 762
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 421
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 6698
telemt_me_writer_restored_same_endpoint_total 6314
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 382
telemt_user_connections_total{user="hello"} 431242
telemt_user_connections_current{user="hello"} 686
telemt_user_octets_from_client{user="hello"} 6276310288 (5.85 GB)
telemt_user_octets_to_client{user="hello"} 133735913188 (124.55 GB)
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 21813.3 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470310
telemt_connections_bad_total 159644
telemt_handshake_timeouts_total 11696
telemt_upstream_connect_attempt_total 12571
telemt_upstream_connect_success_total 12570
telemt_upstream_connect_attempts_per_request{bucket="1"} 12570
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7390
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5180
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 2707
telemt_me_reconnect_success_total 2688
telemt_me_reader_eof_total 2762
telemt_me_idle_close_by_peer_total 2762
telemt_me_route_drop_no_conn_total 146251
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 351
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2768
telemt_me_writer_restored_same_endpoint_total 2687
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 262701
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 4587459272 (4.27 GB)
telemt_user_octets_to_client{user="hello"} 92639013648 (86.28 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 22497.5 (6h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 403687
telemt_connections_bad_total 11052
telemt_handshake_timeouts_total 3614
telemt_upstream_connect_attempt_total 9886
telemt_upstream_connect_success_total 9873
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 1769
telemt_me_reconnect_success_total 1752
telemt_me_reader_eof_total 1847
telemt_me_idle_close_by_peer_total 1846
telemt_me_route_drop_no_conn_total 196902
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 765
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 498
telemt_desync_frames_bucket_total{bucket="1_2"} 347
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1851
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 370637
telemt_user_connections_current{user="hello"} 665
telemt_user_octets_from_client{user="hello"} 15448199388 (14.39 GB)
telemt_user_octets_to_client{user="hello"} 190441649216 (177.36 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 131
```