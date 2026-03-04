# Server Metrics 2026-03-04 08:58:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 42485.2 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523348
telemt_connections_bad_total 8112
telemt_handshake_timeouts_total 6654
telemt_upstream_connect_attempt_total 26637
telemt_upstream_connect_success_total 26521
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26521
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 283
telemt_me_reconnect_attempts_total 5387
telemt_me_reconnect_success_total 5349
telemt_me_reader_eof_total 5488
telemt_me_idle_close_by_peer_total 5488
telemt_me_route_drop_no_conn_total 180650
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 938
telemt_desync_full_logged_total 340
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 272
telemt_desync_frames_bucket_total{bucket="3_10"} 352
telemt_desync_frames_bucket_total{bucket="gt_10"} 314
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5488
telemt_me_writer_restored_same_endpoint_total 5328
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 441483
telemt_user_connections_current{user="hello"} 1001
telemt_user_octets_from_client{user="hello"} 5144524432 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 132010955504 (122.94 GB)
telemt_user_unique_ips_current{user="hello"} 123
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 42481.8 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214815
telemt_connections_bad_total 1966
telemt_handshake_timeouts_total 24307
telemt_upstream_connect_attempt_total 87794
telemt_upstream_connect_success_total 86534
telemt_upstream_connect_fail_total 591
telemt_upstream_connect_attempts_per_request{bucket="1"} 86528
telemt_upstream_connect_attempts_per_request{bucket="2"} 597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 591
telemt_me_keepalive_timeout_total 1267
telemt_me_reconnect_attempts_total 51034
telemt_me_reconnect_success_total 50954
telemt_me_reader_eof_total 52257
telemt_me_idle_close_by_peer_total 52256
telemt_me_route_drop_no_conn_total 98599
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 182
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 483
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 96
telemt_desync_frames_bucket_total{bucket="3_10"} 223
telemt_desync_frames_bucket_total{bucket="gt_10"} 164
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 52337
telemt_me_writer_restored_same_endpoint_total 50929
telemt_me_writer_removed_unexpected_minus_restored_total 1408
telemt_user_connections_total{user="hello"} 160414
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 1940101828 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 58192268736 (54.20 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 42480.5 (11h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 441875
telemt_connections_bad_total 125306
telemt_handshake_timeouts_total 12683
telemt_upstream_connect_attempt_total 61808
telemt_upstream_connect_success_total 61421
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 61420
telemt_upstream_connect_attempts_per_request{bucket="2"} 185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25939
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 825
telemt_me_reconnect_attempts_total 28070
telemt_me_reconnect_success_total 27996
telemt_me_reader_eof_total 29551
telemt_me_idle_close_by_peer_total 29548
telemt_me_route_drop_no_conn_total 146644
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 674
telemt_desync_full_logged_total 254
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 247
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 29562
telemt_me_writer_restored_same_endpoint_total 27975
telemt_me_writer_removed_unexpected_minus_restored_total 1587
telemt_user_connections_total{user="hello"} 288515
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 2796809092 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 109391035184 (101.88 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 42479.5 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268693
telemt_connections_bad_total 20327
telemt_handshake_timeouts_total 27022
telemt_upstream_connect_attempt_total 31517
telemt_upstream_connect_success_total 31388
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 31388
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 6536
telemt_me_reconnect_success_total 6515
telemt_me_reader_eof_total 6640
telemt_me_idle_close_by_peer_total 6640
telemt_me_route_drop_no_conn_total 80991
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 168
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6640
telemt_me_writer_restored_same_endpoint_total 6494
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 200045
telemt_user_connections_current{user="hello"} 393
telemt_user_octets_from_client{user="hello"} 2237151728 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 69834282020 (65.04 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 42478.2 (11h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411698
telemt_connections_bad_total 6449
telemt_handshake_timeouts_total 132055
telemt_upstream_connect_attempt_total 65607
telemt_upstream_connect_success_total 65187
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65187
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 178
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 853
telemt_me_reconnect_attempts_total 32213
telemt_me_reconnect_success_total 32187
telemt_me_reader_eof_total 33798
telemt_me_idle_close_by_peer_total 33797
telemt_me_route_drop_no_conn_total 121361
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 288
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 139
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 33811
telemt_me_writer_restored_same_endpoint_total 32162
telemt_me_writer_removed_unexpected_minus_restored_total 1649
telemt_user_connections_total{user="hello"} 258127
telemt_user_connections_current{user="hello"} 526
telemt_user_octets_from_client{user="hello"} 3753526556 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 63893705620 (59.51 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 53
```