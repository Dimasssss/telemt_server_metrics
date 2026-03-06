# Server Metrics 2026-03-06 06:41:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 29976.1 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272894
telemt_connections_bad_total 16101
telemt_handshake_timeouts_total 3760
telemt_upstream_connect_attempt_total 29846
telemt_upstream_connect_success_total 29581
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 29581
telemt_upstream_connect_attempts_per_request{bucket="2"} 120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 10419
telemt_me_reconnect_success_total 10379
telemt_me_reader_eof_total 10730
telemt_me_idle_close_by_peer_total 10730
telemt_me_route_drop_no_conn_total 94510
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 911
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 635
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 316
telemt_desync_frames_bucket_total{bucket="gt_10"} 356
telemt_pool_swap_total 4
telemt_pool_force_close_total 208
telemt_me_writer_removed_unexpected_total 10732
telemt_me_writer_restored_same_endpoint_total 10373
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 241509
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 8717929388 (8.12 GB)
telemt_user_octets_to_client{user="hello"} 87684043528 (81.66 GB)
telemt_user_unique_ips_current{user="hello"} 239
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 29971.5 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115467
telemt_connections_bad_total 163
telemt_handshake_timeouts_total 11395
telemt_upstream_connect_attempt_total 25157
telemt_upstream_connect_success_total 25155
telemt_upstream_connect_attempts_per_request{bucket="1"} 25155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10962
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 6777
telemt_me_reconnect_success_total 6750
telemt_me_reader_eof_total 6901
telemt_me_idle_close_by_peer_total 6901
telemt_me_route_drop_no_conn_total 33098
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 378
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 10
telemt_pool_force_close_total 197
telemt_pool_stale_pick_total 2124
telemt_me_writer_removed_unexpected_total 6902
telemt_me_writer_restored_same_endpoint_total 6743
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 101874
telemt_user_connections_current{user="hello"} 365
telemt_user_octets_from_client{user="hello"} 1120748668 (1.04 GB)
telemt_user_octets_to_client{user="hello"} 33893745292 (31.57 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 29968.9 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 195301
telemt_connections_bad_total 1759
telemt_handshake_timeouts_total 4809
telemt_upstream_connect_attempt_total 34480
telemt_upstream_connect_success_total 34226
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 34226
telemt_upstream_connect_attempts_per_request{bucket="2"} 115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 479
telemt_me_reconnect_attempts_total 12927
telemt_me_reconnect_success_total 12888
telemt_me_reader_eof_total 13480
telemt_me_idle_close_by_peer_total 13478
telemt_me_route_drop_no_conn_total 58957
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 367
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 247
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 13507
telemt_me_writer_restored_same_endpoint_total 12866
telemt_me_writer_restored_fallback_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 173490
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 1783398336 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 56720050796 (52.82 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 29965.5 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156342
telemt_connections_bad_total 15363
telemt_handshake_timeouts_total 6445
telemt_upstream_connect_attempt_total 21666
telemt_upstream_connect_success_total 21593
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 21593
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8683
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 233
telemt_me_reconnect_attempts_total 4883
telemt_me_reconnect_success_total 4851
telemt_me_reader_eof_total 5021
telemt_me_idle_close_by_peer_total 5021
telemt_me_route_drop_no_conn_total 51401
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 359
telemt_desync_full_logged_total 114
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 70
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 10
telemt_pool_force_close_total 244
telemt_me_writer_removed_unexpected_total 5022
telemt_me_writer_restored_same_endpoint_total 4844
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 128309
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 1901128448 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 43574172020 (40.58 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 29964.8 (8h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 169301
telemt_connections_bad_total 3276
telemt_handshake_timeouts_total 980
telemt_upstream_connect_attempt_total 20635
telemt_upstream_connect_success_total 20588
telemt_upstream_connect_attempts_per_request{bucket="1"} 20588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 317
telemt_me_reconnect_attempts_total 3701
telemt_me_reconnect_success_total 3685
telemt_me_reader_eof_total 3803
telemt_me_idle_close_by_peer_total 3802
telemt_me_route_drop_no_conn_total 64464
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 372
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 179
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 10
telemt_pool_force_close_total 208
telemt_pool_stale_pick_total 5
telemt_me_writer_removed_unexpected_total 3818
telemt_me_writer_restored_same_endpoint_total 3678
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 161878
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 24251535812 (22.59 GB)
telemt_user_octets_to_client{user="hello"} 99475176740 (92.64 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 73
```