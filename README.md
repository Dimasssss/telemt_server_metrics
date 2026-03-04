# Server Metrics 2026-03-04 03:00:00 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 20961.7 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132459
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 1294
telemt_upstream_connect_attempt_total 16858
telemt_upstream_connect_success_total 16787
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 16787
telemt_upstream_connect_attempts_per_request{bucket="2"} 31
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9463
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7301
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 175
telemt_me_reconnect_attempts_total 4237
telemt_me_reconnect_success_total 4228
telemt_me_reader_eof_total 4326
telemt_me_idle_close_by_peer_total 4326
telemt_me_route_drop_no_conn_total 46978
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 241
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4326
telemt_me_writer_restored_same_endpoint_total 4208
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 126827
telemt_user_connections_current{user="hello"} 297
telemt_user_octets_from_client{user="hello"} 1103616256 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 37563125288 (34.98 GB)
telemt_user_unique_ips_current{user="hello"} 78
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 20958.3 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62252
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 16167
telemt_upstream_connect_attempt_total 51237
telemt_upstream_connect_success_total 50698
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 50692
telemt_upstream_connect_attempts_per_request{bucket="2"} 259
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 861
telemt_me_reconnect_attempts_total 31814
telemt_me_reconnect_success_total 31794
telemt_me_reader_eof_total 32607
telemt_me_idle_close_by_peer_total 32606
telemt_me_route_drop_no_conn_total 20529
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 93
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 91
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 32668
telemt_me_writer_restored_same_endpoint_total 31774
telemt_me_writer_removed_unexpected_minus_restored_total 894
telemt_user_connections_total{user="hello"} 45069
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 355311132 (338.85 MB)
telemt_user_octets_to_client{user="hello"} 24266807232 (22.60 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 20957.1 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146897
telemt_connections_bad_total 53223
telemt_handshake_timeouts_total 3320
telemt_upstream_connect_attempt_total 26088
telemt_upstream_connect_success_total 25905
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 25905
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10578
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 9587
telemt_me_reconnect_success_total 9564
telemt_me_reader_eof_total 9987
telemt_me_idle_close_by_peer_total 9985
telemt_me_route_drop_no_conn_total 28471
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 91
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 289
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 189
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 106
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 9989
telemt_me_writer_restored_same_endpoint_total 9543
telemt_me_writer_removed_unexpected_minus_restored_total 446
telemt_user_connections_total{user="hello"} 86961
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 527263512 (502.84 MB)
telemt_user_octets_to_client{user="hello"} 20938811652 (19.50 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 20956.1 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66165
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 654
telemt_upstream_connect_attempt_total 13577
telemt_upstream_connect_success_total 13508
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 13508
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 1916
telemt_me_reconnect_success_total 1920
telemt_me_reader_eof_total 1928
telemt_me_idle_close_by_peer_total 1928
telemt_me_route_drop_no_conn_total 22866
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 89
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 24
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 13
telemt_pool_swap_total 7
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1928
telemt_me_writer_restored_same_endpoint_total 1900
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 64159
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 520764520 (496.64 MB)
telemt_user_octets_to_client{user="hello"} 22602758176 (21.05 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 20954.9 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158908
telemt_connections_bad_total 93
telemt_handshake_timeouts_total 72060
telemt_upstream_connect_attempt_total 30750
telemt_upstream_connect_success_total 30554
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 30554
telemt_upstream_connect_attempts_per_request{bucket="2"} 93
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 410
telemt_me_reconnect_attempts_total 15204
telemt_me_reconnect_success_total 15201
telemt_me_reader_eof_total 16132
telemt_me_idle_close_by_peer_total 16131
telemt_me_route_drop_no_conn_total 42947
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 44
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2376
telemt_me_writer_removed_unexpected_total 16137
telemt_me_writer_restored_same_endpoint_total 15177
telemt_me_writer_removed_unexpected_minus_restored_total 960
telemt_user_connections_total{user="hello"} 83728
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 478216864 (456.06 MB)
telemt_user_octets_to_client{user="hello"} 19279062980 (17.96 GB)
telemt_user_unique_ips_current{user="hello"} 18
```