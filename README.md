# Server Metrics 2026-03-04 07:36:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 37561.6 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 411360
telemt_connections_bad_total 6637
telemt_handshake_timeouts_total 5957
telemt_upstream_connect_attempt_total 23783
telemt_upstream_connect_success_total 23671
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23671
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 4770
telemt_me_reconnect_success_total 4740
telemt_me_reader_eof_total 4850
telemt_me_idle_close_by_peer_total 4850
telemt_me_route_drop_no_conn_total 134550
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 786
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 489
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 275
telemt_desync_frames_bucket_total{bucket="gt_10"} 277
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4850
telemt_me_writer_restored_same_endpoint_total 4719
telemt_me_writer_removed_unexpected_minus_restored_total 131
telemt_user_connections_total{user="hello"} 342789
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 4042965248 (3.77 GB)
telemt_user_octets_to_client{user="hello"} 103209155952 (96.12 GB)
telemt_user_unique_ips_current{user="hello"} 95
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 37558.2 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173891
telemt_connections_bad_total 1410
telemt_handshake_timeouts_total 23186
telemt_upstream_connect_attempt_total 76744
telemt_upstream_connect_success_total 75623
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 75617
telemt_upstream_connect_attempts_per_request{bucket="2"} 528
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 1190
telemt_me_reconnect_attempts_total 44705
telemt_me_reconnect_success_total 44626
telemt_me_reader_eof_total 45725
telemt_me_idle_close_by_peer_total 45724
telemt_me_route_drop_no_conn_total 64761
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 162
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 347
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 230
telemt_desync_frames_bucket_total{bucket="1_2"} 81
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 45805
telemt_me_writer_restored_same_endpoint_total 44601
telemt_me_writer_removed_unexpected_minus_restored_total 1204
telemt_user_connections_total{user="hello"} 122280
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 1301087528 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 47948665332 (44.66 GB)
telemt_user_unique_ips_current{user="hello"} 53
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 37556.9 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344406
telemt_connections_bad_total 105949
telemt_handshake_timeouts_total 10233
telemt_upstream_connect_attempt_total 56210
telemt_upstream_connect_success_total 55880
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 55879
telemt_upstream_connect_attempts_per_request{bucket="2"} 157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23671
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 738
telemt_me_reconnect_attempts_total 25413
telemt_me_reconnect_success_total 25347
telemt_me_reader_eof_total 26726
telemt_me_idle_close_by_peer_total 26723
telemt_me_route_drop_no_conn_total 103334
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 159
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 524
telemt_desync_full_logged_total 197
telemt_desync_suppressed_total 327
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 26737
telemt_me_writer_restored_same_endpoint_total 25326
telemt_me_writer_removed_unexpected_minus_restored_total 1411
telemt_user_connections_total{user="hello"} 218923
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 2003843576 (1.87 GB)
telemt_user_octets_to_client{user="hello"} 78675189972 (73.27 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 37555.9 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197710
telemt_connections_bad_total 15908
telemt_handshake_timeouts_total 7590
telemt_upstream_connect_attempt_total 28726
telemt_upstream_connect_success_total 28605
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 28605
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10891
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 6177
telemt_me_reconnect_success_total 6163
telemt_me_reader_eof_total 6282
telemt_me_idle_close_by_peer_total 6282
telemt_me_route_drop_no_conn_total 63196
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
telemt_me_writer_removed_unexpected_total 6282
telemt_me_writer_restored_same_endpoint_total 6142
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 155471
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 1638758672 (1.53 GB)
telemt_user_octets_to_client{user="hello"} 55560409456 (51.74 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 37554.5 (10h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 340609
telemt_connections_bad_total 6429
telemt_handshake_timeouts_total 129870
telemt_upstream_connect_attempt_total 53307
telemt_upstream_connect_success_total 52954
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 52954
telemt_upstream_connect_attempts_per_request{bucket="2"} 164
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 718
telemt_me_reconnect_attempts_total 24648
telemt_me_reconnect_success_total 24630
telemt_me_reader_eof_total 25931
telemt_me_idle_close_by_peer_total 25930
telemt_me_route_drop_no_conn_total 93350
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 160
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
telemt_me_writer_removed_unexpected_total 25943
telemt_me_writer_restored_same_endpoint_total 24605
telemt_me_writer_removed_unexpected_minus_restored_total 1338
telemt_user_connections_total{user="hello"} 197791
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 2540229200 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 44203507628 (41.17 GB)
telemt_user_unique_ips_current{user="hello"} 42
```