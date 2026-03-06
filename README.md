# Server Metrics 2026-03-06 16:00:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 20342.2 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 613607
telemt_connections_bad_total 7322
telemt_handshake_timeouts_total 2971
telemt_upstream_connect_attempt_total 9987
telemt_upstream_connect_success_total 9926
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 9952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4613
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 134
telemt_me_reconnect_attempts_total 1975
telemt_me_reconnect_success_total 1961
telemt_me_reader_eof_total 2059
telemt_me_idle_close_by_peer_total 2059
telemt_me_route_drop_no_conn_total 251124
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3190
telemt_desync_full_logged_total 773
telemt_desync_suppressed_total 2417
telemt_desync_frames_bucket_total{bucket="1_2"} 758
telemt_desync_frames_bucket_total{bucket="3_10"} 1097
telemt_desync_frames_bucket_total{bucket="gt_10"} 1335
telemt_pool_swap_total 4
telemt_pool_force_close_total 233
telemt_me_writer_removed_unexpected_total 2061
telemt_me_writer_restored_same_endpoint_total 1955
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 525612
telemt_user_connections_current{user="hello"} 1244
telemt_user_octets_from_client{user="hello"} 12375265020 (11.53 GB)
telemt_user_octets_to_client{user="hello"} 198510277168 (184.88 GB)
telemt_user_unique_ips_current{user="hello"} 334
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 20342.0 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228573
telemt_connections_bad_total 866
telemt_handshake_timeouts_total 6819
telemt_upstream_connect_attempt_total 9518
telemt_upstream_connect_success_total 9496
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 9518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4573
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4922
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 930
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 962
telemt_me_route_drop_no_conn_total 118602
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 788
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 529
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 290
telemt_desync_frames_bucket_total{bucket="gt_10"} 357
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 963
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 211266
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 2394488836 (2.23 GB)
telemt_user_octets_to_client{user="hello"} 86409288484 (80.47 GB)
telemt_user_unique_ips_current{user="hello"} 135
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 20341.9 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 460594
telemt_connections_bad_total 5384
telemt_handshake_timeouts_total 43872
telemt_upstream_connect_attempt_total 16547
telemt_upstream_connect_success_total 16470
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 16535
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7354
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 5437
telemt_me_reconnect_success_total 5415
telemt_me_reader_eof_total 5725
telemt_me_idle_close_by_peer_total 5725
telemt_me_route_drop_no_conn_total 227363
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 938
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 359
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5737
telemt_me_writer_restored_same_endpoint_total 5408
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 396593
telemt_user_connections_current{user="hello"} 730
telemt_user_octets_from_client{user="hello"} 5874511264 (5.47 GB)
telemt_user_octets_to_client{user="hello"} 125957654680 (117.31 GB)
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 19658.0 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388074
telemt_connections_bad_total 111167
telemt_handshake_timeouts_total 10427
telemt_upstream_connect_attempt_total 10451
telemt_upstream_connect_success_total 10450
telemt_upstream_connect_attempts_per_request{bucket="1"} 10450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4219
telemt_me_keepalive_timeout_total 124
telemt_me_reconnect_attempts_total 1985
telemt_me_reconnect_success_total 1969
telemt_me_reader_eof_total 2006
telemt_me_idle_close_by_peer_total 2006
telemt_me_route_drop_no_conn_total 121502
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 321
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 205
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2012
telemt_me_writer_restored_same_endpoint_total 1968
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 231264
telemt_user_connections_current{user="hello"} 608
telemt_user_octets_from_client{user="hello"} 2667252500 (2.48 GB)
telemt_user_octets_to_client{user="hello"} 82478863464 (76.81 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 20342.2 (5h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 357375
telemt_connections_bad_total 11042
telemt_handshake_timeouts_total 2831
telemt_upstream_connect_attempt_total 9572
telemt_upstream_connect_success_total 9560
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5192
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 1764
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1844
telemt_me_idle_close_by_peer_total 1843
telemt_me_route_drop_no_conn_total 181604
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 79
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 656
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 426
telemt_desync_frames_bucket_total{bucket="1_2"} 299
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 163
telemt_pool_swap_total 6
telemt_pool_force_close_total 240
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_restored_same_endpoint_total 1746
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 328039
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 15071798816 (14.04 GB)
telemt_user_octets_to_client{user="hello"} 174037850828 (162.09 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 147
```