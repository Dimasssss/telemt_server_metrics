# Server Metrics 2026-03-04 01:43:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 16355.5 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 107057
telemt_connections_bad_total 1367
telemt_handshake_timeouts_total 633
telemt_upstream_connect_attempt_total 13499
telemt_upstream_connect_success_total 13438
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 13438
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 3560
telemt_me_reconnect_success_total 3558
telemt_me_reader_eof_total 3639
telemt_me_idle_close_by_peer_total 3639
telemt_me_route_drop_no_conn_total 39409
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 3639
telemt_me_writer_restored_same_endpoint_total 3538
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 102643
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 795364704 (758.52 MB)
telemt_user_octets_to_client{user="hello"} 31678588032 (29.50 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 16352.1 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50420
telemt_connections_bad_total 111
telemt_handshake_timeouts_total 12600
telemt_upstream_connect_attempt_total 35237
telemt_upstream_connect_success_total 34827
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 34821
telemt_upstream_connect_attempts_per_request{bucket="2"} 194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23765
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11043
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 702
telemt_me_reconnect_attempts_total 20663
telemt_me_reconnect_success_total 20651
telemt_me_reader_eof_total 21184
telemt_me_idle_close_by_peer_total 21183
telemt_me_route_drop_no_conn_total 17346
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 21245
telemt_me_writer_restored_same_endpoint_total 20631
telemt_me_writer_removed_unexpected_minus_restored_total 614
telemt_user_connections_total{user="hello"} 37126
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 287322968 (274.01 MB)
telemt_user_octets_to_client{user="hello"} 22192385676 (20.67 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 16351.0 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117672
telemt_connections_bad_total 41169
telemt_handshake_timeouts_total 2026
telemt_upstream_connect_attempt_total 18249
telemt_upstream_connect_success_total 18138
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 18138
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 222
telemt_me_reconnect_attempts_total 6144
telemt_me_reconnect_success_total 6136
telemt_me_reader_eof_total 6385
telemt_me_idle_close_by_peer_total 6383
telemt_me_route_drop_no_conn_total 22296
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 244
telemt_desync_full_logged_total 81
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 103
telemt_pool_swap_total 2
telemt_pool_force_close_total 61
telemt_me_writer_removed_unexpected_total 6386
telemt_me_writer_restored_same_endpoint_total 6115
telemt_me_writer_removed_unexpected_minus_restored_total 271
telemt_user_connections_total{user="hello"} 72220
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 438968016 (418.63 MB)
telemt_user_octets_to_client{user="hello"} 18109657808 (16.87 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 16349.9 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52986
telemt_connections_bad_total 172
telemt_handshake_timeouts_total 535
telemt_upstream_connect_attempt_total 10309
telemt_upstream_connect_success_total 10263
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 10263
telemt_upstream_connect_attempts_per_request{bucket="2"} 22
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6348
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 106
telemt_me_reconnect_attempts_total 1445
telemt_me_reconnect_success_total 1453
telemt_me_reader_eof_total 1458
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 18510
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 5
telemt_pool_force_close_total 119
telemt_me_writer_removed_unexpected_total 1458
telemt_me_writer_restored_same_endpoint_total 1433
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 51353
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 429550308 (409.65 MB)
telemt_user_octets_to_client{user="hello"} 15973249096 (14.88 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 16348.4 (4h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127976
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 56230
telemt_upstream_connect_attempt_total 24921
telemt_upstream_connect_success_total 24778
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 24778
telemt_upstream_connect_attempts_per_request{bucket="2"} 67
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 337
telemt_me_reconnect_attempts_total 13209
telemt_me_reconnect_success_total 13209
telemt_me_reader_eof_total 14061
telemt_me_idle_close_by_peer_total 14060
telemt_me_route_drop_no_conn_total 38816
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 76
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1013
telemt_me_writer_removed_unexpected_total 14066
telemt_me_writer_restored_same_endpoint_total 13185
telemt_me_writer_removed_unexpected_minus_restored_total 881
telemt_user_connections_total{user="hello"} 69318
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 328686620 (313.46 MB)
telemt_user_octets_to_client{user="hello"} 16132680792 (15.02 GB)
telemt_user_unique_ips_current{user="hello"} 27
```