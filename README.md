# Server Metrics 2026-03-04 01:58:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 17276.3 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112802
telemt_connections_bad_total 1374
telemt_handshake_timeouts_total 987
telemt_upstream_connect_attempt_total 14773
telemt_upstream_connect_success_total 14712
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 14712
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8321
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 4036
telemt_me_reconnect_success_total 4032
telemt_me_reader_eof_total 4124
telemt_me_idle_close_by_peer_total 4124
telemt_me_route_drop_no_conn_total 41160
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 72
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 156
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 100
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 3
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 4124
telemt_me_writer_restored_same_endpoint_total 4012
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 107861
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 857946504 (818.20 MB)
telemt_user_octets_to_client{user="hello"} 32744188208 (30.50 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 17273.0 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52570
telemt_connections_bad_total 164
telemt_handshake_timeouts_total 13207
telemt_upstream_connect_attempt_total 38302
telemt_upstream_connect_success_total 37881
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 37875
telemt_upstream_connect_attempts_per_request{bucket="2"} 199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25830
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12032
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_timeout_total 732
telemt_me_reconnect_attempts_total 22785
telemt_me_reconnect_success_total 22769
telemt_me_reader_eof_total 23353
telemt_me_idle_close_by_peer_total 23352
telemt_me_route_drop_no_conn_total 17987
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 79
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 23414
telemt_me_writer_restored_same_endpoint_total 22749
telemt_me_writer_removed_unexpected_minus_restored_total 665
telemt_user_connections_total{user="hello"} 38594
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 296035908 (282.32 MB)
telemt_user_octets_to_client{user="hello"} 22570393092 (21.02 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 17271.7 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123681
telemt_connections_bad_total 43547
telemt_handshake_timeouts_total 2819
telemt_upstream_connect_attempt_total 19489
telemt_upstream_connect_success_total 19372
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 19372
telemt_upstream_connect_attempts_per_request{bucket="2"} 53
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7967
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 239
telemt_me_reconnect_attempts_total 6534
telemt_me_reconnect_success_total 6525
telemt_me_reader_eof_total 6800
telemt_me_idle_close_by_peer_total 6798
telemt_me_route_drop_no_conn_total 23523
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 256
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 171
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 6801
telemt_me_writer_restored_same_endpoint_total 6504
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 74766
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 451666672 (430.74 MB)
telemt_user_octets_to_client{user="hello"} 18514342776 (17.24 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 17270.6 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55368
telemt_connections_bad_total 176
telemt_handshake_timeouts_total 542
telemt_upstream_connect_attempt_total 10884
telemt_upstream_connect_success_total 10835
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 10835
telemt_upstream_connect_attempts_per_request{bucket="2"} 24
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1534
telemt_me_reconnect_success_total 1541
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 19131
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 73
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 120
telemt_me_writer_removed_unexpected_total 1546
telemt_me_writer_restored_same_endpoint_total 1521
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 53662
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 442456140 (421.96 MB)
telemt_user_octets_to_client{user="hello"} 18013149692 (16.78 GB)
telemt_user_unique_ips_current{user="hello"} 29
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 17269.4 (4h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133597
telemt_connections_bad_total 59
telemt_handshake_timeouts_total 59218
telemt_upstream_connect_attempt_total 25630
telemt_upstream_connect_success_total 25466
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 25466
telemt_upstream_connect_attempts_per_request{bucket="2"} 78
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 13361
telemt_me_reconnect_success_total 13361
telemt_me_reader_eof_total 14217
telemt_me_idle_close_by_peer_total 14216
telemt_me_route_drop_no_conn_total 39343
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 74
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 103
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1500
telemt_me_writer_removed_unexpected_total 14222
telemt_me_writer_restored_same_endpoint_total 13337
telemt_me_writer_removed_unexpected_minus_restored_total 885
telemt_user_connections_total{user="hello"} 71797
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 360452584 (343.75 MB)
telemt_user_octets_to_client{user="hello"} 16549803432 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 15
```