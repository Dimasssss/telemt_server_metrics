# Server Metrics 2026-03-04 21:02:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 553.5 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11133
telemt_handshake_timeouts_total 87
telemt_upstream_connect_attempt_total 122
telemt_upstream_connect_success_total 115
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 115
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 1170
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 8
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_user_connections_total{user="hello"} 7610
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 508971524 (485.39 MB)
telemt_user_octets_to_client{user="hello"} 1682416268 (1.57 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 548.3 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3351
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 138
telemt_upstream_connect_success_total 132
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 132
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 19
telemt_me_route_drop_no_conn_total 667
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 16
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 3
telemt_user_connections_total{user="hello"} 2856
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 21387496 (20.40 MB)
telemt_user_octets_to_client{user="hello"} 886536568 (845.47 MB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 545.0 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7263
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 110
telemt_upstream_connect_attempt_total 126
telemt_upstream_connect_success_total 123
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 123
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 1573
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 22
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_user_connections_total{user="hello"} 6648
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 55980552 (53.39 MB)
telemt_user_octets_to_client{user="hello"} 1384047548 (1.29 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 32593.1 (9h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477521
telemt_connections_bad_total 59764
telemt_handshake_timeouts_total 14561
telemt_upstream_connect_attempt_total 13670
telemt_upstream_connect_success_total 13670
telemt_upstream_connect_attempts_per_request{bucket="1"} 13670
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 1823
telemt_me_reconnect_success_total 1814
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 166623
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 133
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 628
telemt_desync_full_logged_total 272
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 171
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 11
telemt_pool_force_close_total 363
telemt_me_writer_removed_unexpected_total 1841
telemt_me_writer_restored_same_endpoint_total 1790
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 377640
telemt_user_connections_current{user="hello"} 395
telemt_user_octets_from_client{user="hello"} 5465217820 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 145135235508 (135.17 GB)
telemt_user_unique_ips_current{user="hello"} 35
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 32952.6 (9h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 483541
telemt_connections_bad_total 3749
telemt_handshake_timeouts_total 5301
telemt_upstream_connect_attempt_total 18540
telemt_upstream_connect_success_total 18448
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 18448
telemt_upstream_connect_attempts_per_request{bucket="2"} 43
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 269
telemt_me_reconnect_attempts_total 3644
telemt_me_reconnect_success_total 3635
telemt_me_reader_eof_total 3761
telemt_me_idle_close_by_peer_total 3761
telemt_me_route_drop_no_conn_total 217730
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 134
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 815
telemt_desync_full_logged_total 294
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 164
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 7
telemt_pool_force_close_total 338
telemt_pool_stale_pick_total 175
telemt_me_writer_removed_unexpected_total 3762
telemt_me_writer_restored_same_endpoint_total 3614
telemt_me_writer_removed_unexpected_minus_restored_total 148
telemt_user_connections_total{user="hello"} 435405
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 6894868748 (6.42 GB)
telemt_user_octets_to_client{user="hello"} 141501388088 (131.78 GB)
telemt_user_unique_ips_current{user="hello"} 40
```