# Server Metrics 2026-03-06 16:06:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 20649.3 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624404
telemt_connections_bad_total 8046
telemt_handshake_timeouts_total 2980
telemt_upstream_connect_attempt_total 10077
telemt_upstream_connect_success_total 10016
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 10042
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4652
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1975
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2059
telemt_me_idle_close_by_peer_total 2059
telemt_me_route_drop_no_conn_total 258313
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3217
telemt_desync_full_logged_total 780
telemt_desync_suppressed_total 2437
telemt_desync_frames_bucket_total{bucket="1_2"} 765
telemt_desync_frames_bucket_total{bucket="3_10"} 1109
telemt_desync_frames_bucket_total{bucket="gt_10"} 1343
telemt_pool_swap_total 4
telemt_pool_force_close_total 233
telemt_me_writer_removed_unexpected_total 2061
telemt_me_writer_restored_same_endpoint_total 1955
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 535449
telemt_user_connections_current{user="hello"} 1180
telemt_user_octets_from_client{user="hello"} 12478532016 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 201631428112 (187.78 GB)
telemt_user_unique_ips_current{user="hello"} 313
telemt_user_unique_ips_recent_window{user="hello"} 171
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 20649.4 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 232661
telemt_connections_bad_total 866
telemt_handshake_timeouts_total 6847
telemt_upstream_connect_attempt_total 9665
telemt_upstream_connect_success_total 9643
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5000
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 123
telemt_me_reconnect_attempts_total 930
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 962
telemt_me_route_drop_no_conn_total 126446
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 798
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 215174
telemt_user_connections_current{user="hello"} 447
telemt_user_octets_from_client{user="hello"} 2428341424 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 87323956472 (81.33 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 20649.2 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470482
telemt_connections_bad_total 5385
telemt_handshake_timeouts_total 47116
telemt_upstream_connect_attempt_total 16752
telemt_upstream_connect_success_total 16675
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 16740
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 5492
telemt_me_reconnect_success_total 5469
telemt_me_reader_eof_total 5780
telemt_me_idle_close_by_peer_total 5780
telemt_me_route_drop_no_conn_total 233537
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 960
telemt_desync_full_logged_total 290
telemt_desync_suppressed_total 670
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 367
telemt_desync_frames_bucket_total{bucket="gt_10"} 365
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5792
telemt_me_writer_restored_same_endpoint_total 5462
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 403015
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 5906686776 (5.50 GB)
telemt_user_octets_to_client{user="hello"} 127741704968 (118.97 GB)
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 19965.3 (5h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400590
telemt_connections_bad_total 118707
telemt_handshake_timeouts_total 10527
telemt_upstream_connect_attempt_total 10669
telemt_upstream_connect_success_total 10668
telemt_upstream_connect_attempts_per_request{bucket="1"} 10668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4308
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 2016
telemt_me_reconnect_success_total 2000
telemt_me_reader_eof_total 2037
telemt_me_idle_close_by_peer_total 2037
telemt_me_route_drop_no_conn_total 125800
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 335
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2043
telemt_me_writer_restored_same_endpoint_total 1999
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 236006
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 2741069980 (2.55 GB)
telemt_user_octets_to_client{user="hello"} 85980451788 (80.08 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 20649.5 (5h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362342
telemt_connections_bad_total 11042
telemt_handshake_timeouts_total 2842
telemt_upstream_connect_attempt_total 9626
telemt_upstream_connect_success_total 9614
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1844
telemt_me_route_drop_no_conn_total 184522
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 669
telemt_desync_full_logged_total 234
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 306
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 6
telemt_pool_force_close_total 240
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 332652
telemt_user_connections_current{user="hello"} 478
telemt_user_octets_from_client{user="hello"} 15103844052 (14.07 GB)
telemt_user_octets_to_client{user="hello"} 175780540172 (163.71 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 89
```