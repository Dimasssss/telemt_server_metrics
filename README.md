# Server Metrics 2026-03-04 22:14:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 4858.4 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56936
telemt_connections_bad_total 1334
telemt_handshake_timeouts_total 423
telemt_upstream_connect_attempt_total 3356
telemt_upstream_connect_success_total 3314
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3314
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 675
telemt_me_reconnect_success_total 687
telemt_me_reader_eof_total 683
telemt_me_idle_close_by_peer_total 683
telemt_me_route_drop_no_conn_total 13987
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 108
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 63
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 47468
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 2209482752 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 22308706792 (20.78 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 4852.9 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20973
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 131
telemt_upstream_connect_attempt_total 3604
telemt_upstream_connect_success_total 3556
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 3556
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1506
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 717
telemt_me_reconnect_success_total 728
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 5856
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 723
telemt_me_writer_restored_same_endpoint_total 709
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 19492
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 179199372 (170.90 MB)
telemt_user_octets_to_client{user="hello"} 5117377504 (4.77 GB)
telemt_user_unique_ips_current{user="hello"} 17
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 4849.7 (1h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47476
telemt_connections_bad_total 781
telemt_handshake_timeouts_total 220
telemt_upstream_connect_attempt_total 1452
telemt_upstream_connect_success_total 1432
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1432
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 19
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 14157
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 130
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 93
telemt_desync_frames_bucket_total{bucket="1_2"} 31
telemt_desync_frames_bucket_total{bucket="3_10"} 43
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 43018
telemt_user_connections_current{user="hello"} 352
telemt_user_octets_from_client{user="hello"} 646273208 (616.33 MB)
telemt_user_octets_to_client{user="hello"} 16593031856 (15.45 GB)
telemt_user_unique_ips_current{user="hello"} 50
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 36897.9 (10h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509540
telemt_connections_bad_total 67241
telemt_handshake_timeouts_total 14642
telemt_upstream_connect_attempt_total 16008
telemt_upstream_connect_success_total 16008
telemt_upstream_connect_attempts_per_request{bucket="1"} 16008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6940
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 2137
telemt_me_reconnect_success_total 2123
telemt_me_reader_eof_total 2163
telemt_me_idle_close_by_peer_total 2163
telemt_me_route_drop_no_conn_total 175945
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 147
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 13
telemt_pool_force_close_total 423
telemt_me_writer_removed_unexpected_total 2164
telemt_me_writer_restored_same_endpoint_total 2099
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 399538
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 5640418100 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 153237638100 (142.71 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 37257.2 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511556
telemt_connections_bad_total 3759
telemt_handshake_timeouts_total 5686
telemt_upstream_connect_attempt_total 21883
telemt_upstream_connect_success_total 21763
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21763
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4560
telemt_me_reconnect_success_total 4548
telemt_me_reader_eof_total 4712
telemt_me_idle_close_by_peer_total 4712
telemt_me_route_drop_no_conn_total 226032
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 826
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4715
telemt_me_writer_restored_same_endpoint_total 4527
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 461833
telemt_user_connections_current{user="hello"} 262
telemt_user_octets_from_client{user="hello"} 7150413596 (6.66 GB)
telemt_user_octets_to_client{user="hello"} 148066591236 (137.90 GB)
telemt_user_unique_ips_current{user="hello"} 42
```