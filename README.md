# Server Metrics 2026-03-06 09:35:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 3814.6 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105719
telemt_connections_bad_total 396
telemt_handshake_timeouts_total 500
telemt_upstream_connect_attempt_total 1068
telemt_upstream_connect_success_total 1064
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 34986
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 527
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 189
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 85229
telemt_user_connections_current{user="hello"} 980
telemt_user_octets_from_client{user="hello"} 1187825636 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 29344975200 (27.33 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 3811.9 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65089
telemt_connections_bad_total 342
telemt_handshake_timeouts_total 29621
telemt_upstream_connect_attempt_total 1776
telemt_upstream_connect_success_total 1775
telemt_upstream_connect_attempts_per_request{bucket="1"} 1775
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 822
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 72
telemt_me_reconnect_success_total 68
telemt_me_reader_eof_total 71
telemt_me_idle_close_by_peer_total 71
telemt_me_route_drop_no_conn_total 13543
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_restored_same_endpoint_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 34411
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 532684824 (508.01 MB)
telemt_user_octets_to_client{user="hello"} 11072624660 (10.31 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 3795.1 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79095
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 10383
telemt_upstream_connect_attempt_total 1841
telemt_upstream_connect_success_total 1825
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 740
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 111
telemt_me_reconnect_success_total 102
telemt_me_reader_eof_total 102
telemt_me_idle_close_by_peer_total 101
telemt_me_route_drop_no_conn_total 24650
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 176
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 126
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 62
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_me_writer_removed_unexpected_total 107
telemt_me_writer_restored_same_endpoint_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 65379
telemt_user_connections_current{user="hello"} 605
telemt_user_octets_from_client{user="hello"} 1241024832 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 17191186152 (16.01 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 3779.7 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62168
telemt_connections_bad_total 3408
telemt_handshake_timeouts_total 11754
telemt_upstream_connect_attempt_total 1871
telemt_upstream_connect_success_total 1853
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 1869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 829
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 165
telemt_me_reconnect_success_total 160
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 22133
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 139
telemt_desync_full_logged_total 49
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_me_writer_removed_unexpected_total 162
telemt_me_writer_restored_same_endpoint_total 158
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 45184
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 775584244 (739.65 MB)
telemt_user_octets_to_client{user="hello"} 12821205984 (11.94 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 3721.3 (1h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54550
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 321
telemt_upstream_connect_attempt_total 1929
telemt_upstream_connect_success_total 1901
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 1927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 297
telemt_me_reconnect_success_total 294
telemt_me_reader_eof_total 295
telemt_me_idle_close_by_peer_total 295
telemt_me_route_drop_no_conn_total 24429
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 98
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 50006
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 879408668 (838.67 MB)
telemt_user_octets_to_client{user="hello"} 22359523884 (20.82 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 98
```