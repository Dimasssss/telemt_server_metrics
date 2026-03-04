# Server Metrics 2026-03-04 09:03:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 42792.2 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536750
telemt_connections_bad_total 8219
telemt_handshake_timeouts_total 6682
telemt_upstream_connect_attempt_total 26964
telemt_upstream_connect_success_total 26848
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 26848
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 289
telemt_me_reconnect_attempts_total 5518
telemt_me_reconnect_success_total 5479
telemt_me_reader_eof_total 5625
telemt_me_idle_close_by_peer_total 5625
telemt_me_route_drop_no_conn_total 186398
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 941
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 598
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 353
telemt_desync_frames_bucket_total{bucket="gt_10"} 315
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 5625
telemt_me_writer_restored_same_endpoint_total 5458
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 451188
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 5215848324 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 134558623044 (125.32 GB)
telemt_user_unique_ips_current{user="hello"} 112
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 42788.8 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218403
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 24330
telemt_upstream_connect_attempt_total 88478
telemt_upstream_connect_success_total 87210
telemt_upstream_connect_fail_total 596
telemt_upstream_connect_attempts_per_request{bucket="1"} 87204
telemt_upstream_connect_attempts_per_request{bucket="2"} 602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28314
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 596
telemt_me_keepalive_timeout_total 1271
telemt_me_reconnect_attempts_total 51401
telemt_me_reconnect_success_total 51321
telemt_me_reader_eof_total 52632
telemt_me_idle_close_by_peer_total 52631
telemt_me_route_drop_no_conn_total 100891
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 184
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 494
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 322
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 230
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 2
telemt_pool_force_close_total 139
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 52712
telemt_me_writer_restored_same_endpoint_total 51296
telemt_me_writer_removed_unexpected_minus_restored_total 1416
telemt_user_connections_total{user="hello"} 163916
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 1957188124 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 58910320212 (54.86 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 42787.6 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450006
telemt_connections_bad_total 126632
telemt_handshake_timeouts_total 12762
telemt_upstream_connect_attempt_total 62086
telemt_upstream_connect_success_total 61694
telemt_upstream_connect_fail_total 187
telemt_upstream_connect_attempts_per_request{bucket="1"} 61693
telemt_upstream_connect_attempts_per_request{bucket="2"} 188
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 187
telemt_me_keepalive_timeout_total 829
telemt_me_reconnect_attempts_total 28137
telemt_me_reconnect_success_total 28063
telemt_me_reader_eof_total 29619
telemt_me_idle_close_by_peer_total 29616
telemt_me_route_drop_no_conn_total 150410
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 181
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 694
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 435
telemt_desync_frames_bucket_total{bucket="1_2"} 200
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 253
telemt_pool_swap_total 4
telemt_pool_force_close_total 200
telemt_me_writer_removed_unexpected_total 29630
telemt_me_writer_restored_same_endpoint_total 28042
telemt_me_writer_removed_unexpected_minus_restored_total 1588
telemt_user_connections_total{user="hello"} 295181
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 2858226636 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 110868338616 (103.25 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 42786.5 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279284
telemt_connections_bad_total 20600
telemt_handshake_timeouts_total 33681
telemt_upstream_connect_attempt_total 31644
telemt_upstream_connect_success_total 31515
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 31515
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11931
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 356
telemt_me_reconnect_attempts_total 6536
telemt_me_reconnect_success_total 6515
telemt_me_reader_eof_total 6640
telemt_me_idle_close_by_peer_total 6640
telemt_me_route_drop_no_conn_total 82455
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 178
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 170
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 12
telemt_pool_force_close_total 292
telemt_me_writer_removed_unexpected_total 6640
telemt_me_writer_restored_same_endpoint_total 6494
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 203878
telemt_user_connections_current{user="hello"} 388
telemt_user_octets_from_client{user="hello"} 2276598720 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 71661107336 (66.74 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 42785.3 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417035
telemt_connections_bad_total 6450
telemt_handshake_timeouts_total 132066
telemt_upstream_connect_attempt_total 66392
telemt_upstream_connect_success_total 65973
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 65973
telemt_upstream_connect_attempts_per_request{bucket="2"} 197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 184
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 860
telemt_me_reconnect_attempts_total 32718
telemt_me_reconnect_success_total 32691
telemt_me_reader_eof_total 34334
telemt_me_idle_close_by_peer_total 34333
telemt_me_route_drop_no_conn_total 124109
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 183
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 308
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 202
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 4
telemt_pool_force_close_total 118
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 34347
telemt_me_writer_restored_same_endpoint_total 32666
telemt_me_writer_removed_unexpected_minus_restored_total 1681
telemt_user_connections_total{user="hello"} 263079
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 3817097200 (3.55 GB)
telemt_user_octets_to_client{user="hello"} 65416691596 (60.92 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 54
```