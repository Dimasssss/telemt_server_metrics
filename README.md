# Server Metrics 2026-03-04 06:55:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 35103.8 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341647
telemt_connections_bad_total 4618
telemt_handshake_timeouts_total 5831
telemt_upstream_connect_attempt_total 22680
telemt_upstream_connect_success_total 22573
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 22573
telemt_upstream_connect_attempts_per_request{bucket="2"} 48
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9736
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 4650
telemt_me_reconnect_success_total 4625
telemt_me_reader_eof_total 4734
telemt_me_idle_close_by_peer_total 4734
telemt_me_route_drop_no_conn_total 118588
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 139
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 743
telemt_desync_full_logged_total 279
telemt_desync_suppressed_total 464
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 266
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4734
telemt_me_writer_restored_same_endpoint_total 4605
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 298038
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 3214143252 (2.99 GB)
telemt_user_octets_to_client{user="hello"} 92662139320 (86.30 GB)
telemt_user_unique_ips_current{user="hello"} 84
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 35100.2 (9h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156472
telemt_connections_bad_total 1221
telemt_handshake_timeouts_total 22670
telemt_upstream_connect_attempt_total 73139
telemt_upstream_connect_success_total 72107
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 72101
telemt_upstream_connect_attempts_per_request{bucket="2"} 484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_keepalive_timeout_total 1158
telemt_me_reconnect_attempts_total 43086
telemt_me_reconnect_success_total 43012
telemt_me_reader_eof_total 44082
telemt_me_idle_close_by_peer_total 44081
telemt_me_route_drop_no_conn_total 53823
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 286
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 187
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 68
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44162
telemt_me_writer_restored_same_endpoint_total 42987
telemt_me_writer_removed_unexpected_minus_restored_total 1175
telemt_user_connections_total{user="hello"} 106134
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1010027032 (963.24 MB)
telemt_user_octets_to_client{user="hello"} 42892233760 (39.95 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 35099.0 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307717
telemt_connections_bad_total 99612
telemt_handshake_timeouts_total 8733
telemt_upstream_connect_attempt_total 50162
telemt_upstream_connect_success_total 49854
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 49853
telemt_upstream_connect_attempts_per_request{bucket="2"} 146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20978
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 657
telemt_me_reconnect_attempts_total 21711
telemt_me_reconnect_success_total 21654
telemt_me_reader_eof_total 22855
telemt_me_idle_close_by_peer_total 22852
telemt_me_route_drop_no_conn_total 80042
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 473
telemt_desync_full_logged_total 176
telemt_desync_suppressed_total 297
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 176
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 22864
telemt_me_writer_restored_same_endpoint_total 21633
telemt_me_writer_removed_unexpected_minus_restored_total 1231
telemt_user_connections_total{user="hello"} 190666
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 1617203104 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 61767637584 (57.53 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 35097.9 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173619
telemt_connections_bad_total 13695
telemt_handshake_timeouts_total 5730
telemt_upstream_connect_attempt_total 27025
telemt_upstream_connect_success_total 26922
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26922
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16680
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10241
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 5987
telemt_me_reconnect_success_total 5975
telemt_me_reader_eof_total 6088
telemt_me_idle_close_by_peer_total 6088
telemt_me_route_drop_no_conn_total 48953
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 145
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6088
telemt_me_writer_restored_same_endpoint_total 5954
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 136661
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 1372440380 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 50336156352 (46.88 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 35096.7 (9h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314025
telemt_connections_bad_total 6395
telemt_handshake_timeouts_total 128469
telemt_upstream_connect_attempt_total 48822
telemt_upstream_connect_success_total 48489
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 48489
telemt_upstream_connect_attempts_per_request{bucket="2"} 156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 659
telemt_me_reconnect_attempts_total 22440
telemt_me_reconnect_success_total 22425
telemt_me_reader_eof_total 23635
telemt_me_idle_close_by_peer_total 23634
telemt_me_route_drop_no_conn_total 80420
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 223
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 23648
telemt_me_writer_restored_same_endpoint_total 22400
telemt_me_writer_removed_unexpected_minus_restored_total 1248
telemt_user_connections_total{user="hello"} 173364
telemt_user_connections_current{user="hello"} 443
telemt_user_octets_from_client{user="hello"} 2345393404 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 39027372260 (36.35 GB)
telemt_user_unique_ips_current{user="hello"} 44
```