# Server Metrics 2026-03-04 09:49:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 45558.4 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633086
telemt_connections_bad_total 10944
telemt_handshake_timeouts_total 7239
telemt_upstream_connect_attempt_total 30225
telemt_upstream_connect_success_total 30097
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30097
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 6793
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 6960
telemt_me_idle_close_by_peer_total 6960
telemt_me_route_drop_no_conn_total 225250
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1095
telemt_desync_full_logged_total 385
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 413
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 6960
telemt_me_writer_restored_same_endpoint_total 6729
telemt_me_writer_removed_unexpected_minus_restored_total 231
telemt_user_connections_total{user="hello"} 521631
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 5778868684 (5.38 GB)
telemt_user_octets_to_client{user="hello"} 153104902332 (142.59 GB)
telemt_user_unique_ips_current{user="hello"} 88
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 45554.8 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249530
telemt_connections_bad_total 2051
telemt_handshake_timeouts_total 25718
telemt_upstream_connect_attempt_total 93714
telemt_upstream_connect_success_total 92410
telemt_upstream_connect_fail_total 614
telemt_upstream_connect_attempts_per_request{bucket="1"} 92404
telemt_upstream_connect_attempts_per_request{bucket="2"} 620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 614
telemt_me_keepalive_timeout_total 1343
telemt_me_reconnect_attempts_total 54316
telemt_me_reconnect_success_total 54234
telemt_me_reader_eof_total 55632
telemt_me_idle_close_by_peer_total 55631
telemt_me_route_drop_no_conn_total 118049
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 194
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 522
telemt_desync_full_logged_total 188
telemt_desync_suppressed_total 334
telemt_desync_frames_bucket_total{bucket="1_2"} 101
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55712
telemt_me_writer_restored_same_endpoint_total 54209
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 191958
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 2149357808 (2.00 GB)
telemt_user_octets_to_client{user="hello"} 65934259536 (61.41 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 45553.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515286
telemt_connections_bad_total 139455
telemt_handshake_timeouts_total 15624
telemt_upstream_connect_attempt_total 65493
telemt_upstream_connect_success_total 65086
telemt_upstream_connect_fail_total 194
telemt_upstream_connect_attempts_per_request{bucket="1"} 65085
telemt_upstream_connect_attempts_per_request{bucket="2"} 195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37723
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 194
telemt_me_keepalive_timeout_total 870
telemt_me_reconnect_attempts_total 29559
telemt_me_reconnect_success_total 29479
telemt_me_reader_eof_total 31088
telemt_me_idle_close_by_peer_total 31085
telemt_me_route_drop_no_conn_total 174333
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 192
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 814
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 246
telemt_desync_frames_bucket_total{bucket="3_10"} 277
telemt_desync_frames_bucket_total{bucket="gt_10"} 291
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 31099
telemt_me_writer_restored_same_endpoint_total 29458
telemt_me_writer_removed_unexpected_minus_restored_total 1641
telemt_user_connections_total{user="hello"} 344203
telemt_user_connections_current{user="hello"} 610
telemt_user_octets_from_client{user="hello"} 3685586952 (3.43 GB)
telemt_user_octets_to_client{user="hello"} 122647358616 (114.22 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 45552.5 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331492
telemt_connections_bad_total 23097
telemt_handshake_timeouts_total 52790
telemt_upstream_connect_attempt_total 32875
telemt_upstream_connect_success_total 32740
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 32740
telemt_upstream_connect_attempts_per_request{bucket="2"} 66
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12348
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 375
telemt_me_reconnect_attempts_total 6596
telemt_me_reconnect_success_total 6574
telemt_me_reader_eof_total 6699
telemt_me_idle_close_by_peer_total 6699
telemt_me_route_drop_no_conn_total 94179
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 98
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6699
telemt_me_writer_restored_same_endpoint_total 6553
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 234416
telemt_user_connections_current{user="hello"} 345
telemt_user_octets_from_client{user="hello"} 2595843352 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 80921747816 (75.36 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 45551.3 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462491
telemt_connections_bad_total 6489
telemt_handshake_timeouts_total 132154
telemt_upstream_connect_attempt_total 68180
telemt_upstream_connect_success_total 67755
telemt_upstream_connect_fail_total 200
telemt_upstream_connect_attempts_per_request{bucket="1"} 67755
telemt_upstream_connect_attempts_per_request{bucket="2"} 200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 200
telemt_me_keepalive_timeout_total 897
telemt_me_reconnect_attempts_total 33514
telemt_me_reconnect_success_total 33484
telemt_me_reader_eof_total 35162
telemt_me_idle_close_by_peer_total 35161
telemt_me_route_drop_no_conn_total 141464
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 191
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 427
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 290
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35174
telemt_me_writer_restored_same_endpoint_total 33459
telemt_me_writer_removed_unexpected_minus_restored_total 1715
telemt_user_connections_total{user="hello"} 304123
telemt_user_connections_current{user="hello"} 509
telemt_user_octets_from_client{user="hello"} 4282107108 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 76231616372 (71.00 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 46
```