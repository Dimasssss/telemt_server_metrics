# Server Metrics 2026-03-04 10:46:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 48943.9 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 741464
telemt_connections_bad_total 11055
telemt_handshake_timeouts_total 8721
telemt_upstream_connect_attempt_total 31535
telemt_upstream_connect_success_total 31401
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 31401
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13988
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 7054
telemt_me_reconnect_success_total 7010
telemt_me_reader_eof_total 7229
telemt_me_idle_close_by_peer_total 7229
telemt_me_route_drop_no_conn_total 290010
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1246
telemt_desync_full_logged_total 430
telemt_desync_suppressed_total 816
telemt_desync_frames_bucket_total{bucket="1_2"} 342
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 426
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7229
telemt_me_writer_restored_same_endpoint_total 6989
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 610730
telemt_user_connections_current{user="hello"} 1016
telemt_user_octets_from_client{user="hello"} 6858175520 (6.39 GB)
telemt_user_octets_to_client{user="hello"} 183350951892 (170.76 GB)
telemt_user_unique_ips_current{user="hello"} 93
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 48940.4 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292486
telemt_connections_bad_total 2741
telemt_handshake_timeouts_total 26887
telemt_upstream_connect_attempt_total 95407
telemt_upstream_connect_success_total 94003
telemt_upstream_connect_fail_total 663
telemt_upstream_connect_attempts_per_request{bucket="1"} 93997
telemt_upstream_connect_attempts_per_request{bucket="2"} 669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30980
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 663
telemt_me_keepalive_timeout_total 1358
telemt_me_reconnect_attempts_total 54477
telemt_me_reconnect_success_total 54393
telemt_me_reader_eof_total 55794
telemt_me_idle_close_by_peer_total 55793
telemt_me_route_drop_no_conn_total 130911
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 583
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 257
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55874
telemt_me_writer_restored_same_endpoint_total 54368
telemt_me_writer_removed_unexpected_minus_restored_total 1506
telemt_user_connections_total{user="hello"} 228460
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 2717301512 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 75935822728 (70.72 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 48939.3 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 582745
telemt_connections_bad_total 148125
telemt_handshake_timeouts_total 17740
telemt_upstream_connect_attempt_total 72504
telemt_upstream_connect_success_total 72067
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 72066
telemt_upstream_connect_attempts_per_request{bucket="2"} 210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_timeout_total 936
telemt_me_reconnect_attempts_total 33550
telemt_me_reconnect_success_total 33464
telemt_me_reader_eof_total 35265
telemt_me_idle_close_by_peer_total 35261
telemt_me_route_drop_no_conn_total 211449
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 206
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 993
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 633
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 331
telemt_desync_frames_bucket_total{bucket="gt_10"} 360
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 35277
telemt_me_writer_restored_same_endpoint_total 33443
telemt_me_writer_removed_unexpected_minus_restored_total 1834
telemt_user_connections_total{user="hello"} 398330
telemt_user_connections_current{user="hello"} 503
telemt_user_octets_from_client{user="hello"} 4911172532 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 137315355052 (127.88 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 48938.4 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381610
telemt_connections_bad_total 26154
telemt_handshake_timeouts_total 66056
telemt_upstream_connect_attempt_total 35598
telemt_upstream_connect_success_total 35455
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 35455
telemt_upstream_connect_attempts_per_request{bucket="2"} 70
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13424
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 7208
telemt_me_reconnect_success_total 7183
telemt_me_reader_eof_total 7325
telemt_me_idle_close_by_peer_total 7325
telemt_me_route_drop_no_conn_total 106722
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 203
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 208
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 7325
telemt_me_writer_restored_same_endpoint_total 7162
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 267647
telemt_user_connections_current{user="hello"} 430
telemt_user_octets_from_client{user="hello"} 2916140348 (2.72 GB)
telemt_user_octets_to_client{user="hello"} 96343996188 (89.73 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 48937.0 (13h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 515061
telemt_connections_bad_total 6810
telemt_handshake_timeouts_total 132353
telemt_upstream_connect_attempt_total 70036
telemt_upstream_connect_success_total 69558
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 69558
telemt_upstream_connect_attempts_per_request{bucket="2"} 226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 914
telemt_me_reconnect_attempts_total 33897
telemt_me_reconnect_success_total 33865
telemt_me_reader_eof_total 35550
telemt_me_idle_close_by_peer_total 35549
telemt_me_route_drop_no_conn_total 161291
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 207
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 573
telemt_desync_full_logged_total 193
telemt_desync_suppressed_total 380
telemt_desync_frames_bucket_total{bucket="1_2"} 118
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35562
telemt_me_writer_restored_same_endpoint_total 33840
telemt_me_writer_removed_unexpected_minus_restored_total 1722
telemt_user_connections_total{user="hello"} 353671
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 4709564548 (4.39 GB)
telemt_user_octets_to_client{user="hello"} 93773989284 (87.33 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 60
```