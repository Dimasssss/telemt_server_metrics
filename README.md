# Server Metrics 2026-03-04 08:38:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 41252.9 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487493
telemt_connections_bad_total 8039
telemt_handshake_timeouts_total 6555
telemt_upstream_connect_attempt_total 25511
telemt_upstream_connect_success_total 25398
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 25398
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 5023
telemt_me_reconnect_success_total 4987
telemt_me_reader_eof_total 5109
telemt_me_idle_close_by_peer_total 5109
telemt_me_route_drop_no_conn_total 165738
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 904
telemt_desync_full_logged_total 328
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 303
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5109
telemt_me_writer_restored_same_endpoint_total 4966
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 413550
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 4853780412 (4.52 GB)
telemt_user_octets_to_client{user="hello"} 123205210656 (114.74 GB)
telemt_user_unique_ips_current{user="hello"} 83
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 41249.4 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202430
telemt_connections_bad_total 1896
telemt_handshake_timeouts_total 24171
telemt_upstream_connect_attempt_total 84943
telemt_upstream_connect_success_total 83711
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 83705
telemt_upstream_connect_attempts_per_request{bucket="2"} 584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56638
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27051
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_keepalive_timeout_total 1252
telemt_me_reconnect_attempts_total 49390
telemt_me_reconnect_success_total 49310
telemt_me_reader_eof_total 50561
telemt_me_idle_close_by_peer_total 50560
telemt_me_route_drop_no_conn_total 89761
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 177
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 450
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 289
telemt_desync_frames_bucket_total{bucket="1_2"} 89
telemt_desync_frames_bucket_total{bucket="3_10"} 209
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 50641
telemt_me_writer_restored_same_endpoint_total 49285
telemt_me_writer_removed_unexpected_minus_restored_total 1356
telemt_user_connections_total{user="hello"} 148795
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 1804621660 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 55527667248 (51.71 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 41248.2 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417541
telemt_connections_bad_total 120278
telemt_handshake_timeouts_total 11955
telemt_upstream_connect_attempt_total 60828
telemt_upstream_connect_success_total 60454
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 60453
telemt_upstream_connect_attempts_per_request{bucket="2"} 179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34629
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_timeout_total 812
telemt_me_reconnect_attempts_total 27843
telemt_me_reconnect_success_total 27771
telemt_me_reader_eof_total 29321
telemt_me_idle_close_by_peer_total 29318
telemt_me_route_drop_no_conn_total 137862
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 174
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 243
telemt_desync_suppressed_total 400
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 230
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29332
telemt_me_writer_restored_same_endpoint_total 27750
telemt_me_writer_removed_unexpected_minus_restored_total 1582
telemt_user_connections_total{user="hello"} 270121
telemt_user_connections_current{user="hello"} 460
telemt_user_octets_from_client{user="hello"} 2625229700 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 102862816852 (95.80 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 41247.1 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235175
telemt_connections_bad_total 19219
telemt_handshake_timeouts_total 9060
telemt_upstream_connect_attempt_total 31016
telemt_upstream_connect_success_total 30887
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 30887
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 352
telemt_me_reconnect_attempts_total 6473
telemt_me_reconnect_success_total 6455
telemt_me_reader_eof_total 6579
telemt_me_idle_close_by_peer_total 6579
telemt_me_route_drop_no_conn_total 76488
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 171
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6579
telemt_me_writer_restored_same_endpoint_total 6434
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 187209
telemt_user_connections_current{user="hello"} 360
telemt_user_octets_from_client{user="hello"} 2106791152 (1.96 GB)
telemt_user_octets_to_client{user="hello"} 65829220264 (61.31 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 41245.9 (11h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390649
telemt_connections_bad_total 6445
telemt_handshake_timeouts_total 132028
telemt_upstream_connect_attempt_total 62142
telemt_upstream_connect_success_total 61733
telemt_upstream_connect_fail_total 192
telemt_upstream_connect_attempts_per_request{bucket="1"} 61733
telemt_upstream_connect_attempts_per_request{bucket="2"} 192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 192
telemt_me_keepalive_timeout_total 821
telemt_me_reconnect_attempts_total 29939
telemt_me_reconnect_success_total 29915
telemt_me_reader_eof_total 31443
telemt_me_idle_close_by_peer_total 31442
telemt_me_route_drop_no_conn_total 112594
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 260
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 31456
telemt_me_writer_restored_same_endpoint_total 29890
telemt_me_writer_removed_unexpected_minus_restored_total 1566
telemt_user_connections_total{user="hello"} 240923
telemt_user_connections_current{user="hello"} 403
telemt_user_octets_from_client{user="hello"} 3143657128 (2.93 GB)
telemt_user_octets_to_client{user="hello"} 60099794236 (55.97 GB)
telemt_user_unique_ips_current{user="hello"} 40
```