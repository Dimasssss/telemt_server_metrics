# Server Metrics 2026-03-04 07:31:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 37254.4 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405872
telemt_connections_bad_total 6613
telemt_handshake_timeouts_total 5931
telemt_upstream_connect_attempt_total 23761
telemt_upstream_connect_success_total 23649
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23649
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 4770
telemt_me_reconnect_success_total 4740
telemt_me_reader_eof_total 4850
telemt_me_idle_close_by_peer_total 4850
telemt_me_route_drop_no_conn_total 132664
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 783
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 488
telemt_desync_frames_bucket_total{bucket="1_2"} 232
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4850
telemt_me_writer_restored_same_endpoint_total 4719
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 337657
telemt_user_connections_current{user="hello"} 762
telemt_user_octets_from_client{user="hello"} 3962909820 (3.69 GB)
telemt_user_octets_to_client{user="hello"} 102216424124 (95.20 GB)
telemt_user_unique_ips_current{user="hello"} 118
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 37251.0 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171460
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 23149
telemt_upstream_connect_attempt_total 76218
telemt_upstream_connect_success_total 75097
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 75091
telemt_upstream_connect_attempts_per_request{bucket="2"} 528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 1186
telemt_me_reconnect_attempts_total 44419
telemt_me_reconnect_success_total 44343
telemt_me_reader_eof_total 45433
telemt_me_idle_close_by_peer_total 45432
telemt_me_route_drop_no_conn_total 62973
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 161
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 338
telemt_desync_full_logged_total 115
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 45513
telemt_me_writer_restored_same_endpoint_total 44318
telemt_me_writer_removed_unexpected_minus_restored_total 1195
telemt_user_connections_total{user="hello"} 120012
telemt_user_connections_current{user="hello"} 371
telemt_user_octets_from_client{user="hello"} 1287083912 (1.20 GB)
telemt_user_octets_to_client{user="hello"} 47298039028 (44.05 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 37249.9 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340059
telemt_connections_bad_total 105162
telemt_handshake_timeouts_total 10119
telemt_upstream_connect_attempt_total 55441
telemt_upstream_connect_success_total 55111
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 55110
telemt_upstream_connect_attempts_per_request{bucket="2"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23336
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 734
telemt_me_reconnect_attempts_total 24919
telemt_me_reconnect_success_total 24856
telemt_me_reader_eof_total 26203
telemt_me_idle_close_by_peer_total 26200
telemt_me_route_drop_no_conn_total 98880
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 521
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 326
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 190
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 26214
telemt_me_writer_restored_same_endpoint_total 24835
telemt_me_writer_removed_unexpected_minus_restored_total 1379
telemt_user_connections_total{user="hello"} 215533
telemt_user_connections_current{user="hello"} 660
telemt_user_octets_from_client{user="hello"} 1934510648 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 76964792024 (71.68 GB)
telemt_user_unique_ips_current{user="hello"} 68
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 37248.7 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195364
telemt_connections_bad_total 15635
telemt_handshake_timeouts_total 7495
telemt_upstream_connect_attempt_total 28443
telemt_upstream_connect_success_total 28322
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 28322
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 314
telemt_me_reconnect_attempts_total 6113
telemt_me_reconnect_success_total 6099
telemt_me_reader_eof_total 6216
telemt_me_idle_close_by_peer_total 6216
telemt_me_route_drop_no_conn_total 61628
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6216
telemt_me_writer_restored_same_endpoint_total 6078
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 153455
telemt_user_connections_current{user="hello"} 278
telemt_user_octets_from_client{user="hello"} 1620956452 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 55129766384 (51.34 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 37247.3 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337426
telemt_connections_bad_total 6423
telemt_handshake_timeouts_total 129699
telemt_upstream_connect_attempt_total 52674
telemt_upstream_connect_success_total 52321
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 52321
telemt_upstream_connect_attempts_per_request{bucket="2"} 164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20885
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 138
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 709
telemt_me_reconnect_attempts_total 24291
telemt_me_reconnect_success_total 24272
telemt_me_reader_eof_total 25561
telemt_me_idle_close_by_peer_total 25560
telemt_me_route_drop_no_conn_total 91531
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 158
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 25573
telemt_me_writer_restored_same_endpoint_total 24247
telemt_me_writer_removed_unexpected_minus_restored_total 1326
telemt_user_connections_total{user="hello"} 194866
telemt_user_connections_current{user="hello"} 338
telemt_user_octets_from_client{user="hello"} 2511326992 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 43171009964 (40.21 GB)
telemt_user_unique_ips_current{user="hello"} 41
```