# Server Metrics 2026-03-06 16:31:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 22188.9 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 665429
telemt_connections_bad_total 10039
telemt_handshake_timeouts_total 3078
telemt_upstream_connect_attempt_total 10799
telemt_upstream_connect_success_total 10733
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 10761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4969
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 2027
telemt_me_reconnect_success_total 2011
telemt_me_reader_eof_total 2111
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 284743
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3433
telemt_desync_full_logged_total 821
telemt_desync_suppressed_total 2612
telemt_desync_frames_bucket_total{bucket="1_2"} 821
telemt_desync_frames_bucket_total{bucket="3_10"} 1184
telemt_desync_frames_bucket_total{bucket="gt_10"} 1428
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2113
telemt_me_writer_restored_same_endpoint_total 2005
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 573453
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 12951641800 (12.06 GB)
telemt_user_octets_to_client{user="hello"} 213833080640 (199.15 GB)
telemt_user_unique_ips_current{user="hello"} 300
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 22188.8 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251470
telemt_connections_bad_total 881
telemt_handshake_timeouts_total 7386
telemt_upstream_connect_attempt_total 10425
telemt_upstream_connect_success_total 10400
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 10425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 955
telemt_me_reconnect_success_total 936
telemt_me_reader_eof_total 987
telemt_me_idle_close_by_peer_total 987
telemt_me_route_drop_no_conn_total 142873
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 823
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 557
telemt_desync_frames_bucket_total{bucket="1_2"} 149
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 372
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 988
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 231036
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 2655601652 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 92878104508 (86.50 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 22188.4 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498615
telemt_connections_bad_total 5426
telemt_handshake_timeouts_total 51358
telemt_upstream_connect_attempt_total 18456
telemt_upstream_connect_success_total 18376
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 18443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8132
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 242
telemt_me_reconnect_attempts_total 6211
telemt_me_reconnect_success_total 6186
telemt_me_reader_eof_total 6537
telemt_me_idle_close_by_peer_total 6537
telemt_me_route_drop_no_conn_total 253223
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1067
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 748
telemt_desync_frames_bucket_total{bucket="1_2"} 251
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 6549
telemt_me_writer_restored_same_endpoint_total 6179
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 368
telemt_user_connections_total{user="hello"} 426136
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 6197174656 (5.77 GB)
telemt_user_octets_to_client{user="hello"} 132575339548 (123.47 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 21504.5 (5h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449567
telemt_connections_bad_total 143974
telemt_handshake_timeouts_total 11634
telemt_upstream_connect_attempt_total 12143
telemt_upstream_connect_success_total 12142
telemt_upstream_connect_attempts_per_request{bucket="1"} 12142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4972
telemt_me_keepalive_timeout_total 147
telemt_me_reconnect_attempts_total 2499
telemt_me_reconnect_success_total 2481
telemt_me_reader_eof_total 2541
telemt_me_idle_close_by_peer_total 2541
telemt_me_route_drop_no_conn_total 142217
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 349
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 85
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2547
telemt_me_writer_restored_same_endpoint_total 2480
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 257836
telemt_user_connections_current{user="hello"} 614
telemt_user_octets_from_client{user="hello"} 4509508740 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 91343436460 (85.07 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 22188.7 (6h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 398567
telemt_connections_bad_total 11051
telemt_handshake_timeouts_total 3541
telemt_upstream_connect_attempt_total 9826
telemt_upstream_connect_success_total 9814
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4419
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 160
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1844
telemt_me_route_drop_no_conn_total 194916
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 757
telemt_desync_full_logged_total 262
telemt_desync_suppressed_total 495
telemt_desync_frames_bucket_total{bucket="1_2"} 341
telemt_desync_frames_bucket_total{bucket="3_10"} 225
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 365819
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 15396466972 (14.34 GB)
telemt_user_octets_to_client{user="hello"} 186965778792 (174.13 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 77
```