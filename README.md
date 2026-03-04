# Server Metrics 2026-03-04 23:10:41 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 8237.2 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83244
telemt_connections_bad_total 1348
telemt_handshake_timeouts_total 530
telemt_upstream_connect_attempt_total 8497
telemt_upstream_connect_success_total 8383
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 8382
telemt_upstream_connect_attempts_per_request{bucket="2"} 35
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3049
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 381
telemt_me_reconnect_attempts_total 3060
telemt_me_reconnect_success_total 3061
telemt_me_reader_eof_total 3138
telemt_me_idle_close_by_peer_total 3137
telemt_me_route_drop_no_conn_total 22070
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 128
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 3187
telemt_me_writer_restored_same_endpoint_total 3041
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 70842
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 2702546916 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 38655407488 (36.00 GB)
telemt_user_unique_ips_current{user="hello"} 37
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 8231.9 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29707
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 9851
telemt_upstream_connect_success_total 9713
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 9710
telemt_upstream_connect_attempts_per_request{bucket="2"} 38
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 520
telemt_me_reconnect_attempts_total 4047
telemt_me_reconnect_success_total 4042
telemt_me_reader_eof_total 4124
telemt_me_idle_close_by_peer_total 4123
telemt_me_route_drop_no_conn_total 9633
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 4178
telemt_me_writer_restored_same_endpoint_total 4023
telemt_me_writer_removed_unexpected_minus_restored_total 155
telemt_user_connections_total{user="hello"} 27977
telemt_user_connections_current{user="hello"} 111
telemt_user_octets_from_client{user="hello"} 249538456 (237.98 MB)
telemt_user_octets_to_client{user="hello"} 8119905892 (7.56 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 8228.5 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70340
telemt_connections_bad_total 1046
telemt_handshake_timeouts_total 430
telemt_upstream_connect_attempt_total 3373
telemt_upstream_connect_success_total 3337
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 3337
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 235
telemt_me_reconnect_success_total 247
telemt_me_reader_eof_total 236
telemt_me_idle_close_by_peer_total 236
telemt_me_route_drop_no_conn_total 21852
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 160
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 112
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 3
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_restored_same_endpoint_total 227
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 64822
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 953261780 (909.10 MB)
telemt_user_octets_to_client{user="hello"} 24477687916 (22.80 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 40276.9 (11h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530541
telemt_connections_bad_total 72944
telemt_handshake_timeouts_total 14697
telemt_upstream_connect_attempt_total 17165
telemt_upstream_connect_success_total 17165
telemt_upstream_connect_attempts_per_request{bucket="1"} 17165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 2188
telemt_me_reconnect_success_total 2172
telemt_me_reader_eof_total 2214
telemt_me_idle_close_by_peer_total 2214
telemt_me_route_drop_no_conn_total 181051
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 163
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 700
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 16
telemt_pool_force_close_total 469
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 2215
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 414560
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 5743157184 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 155985049760 (145.27 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 40636.0 (11h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 525337
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5765
telemt_upstream_connect_attempt_total 25561
telemt_upstream_connect_success_total 25421
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 25421
telemt_upstream_connect_attempts_per_request{bucket="2"} 57
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14689
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 373
telemt_me_reconnect_attempts_total 5645
telemt_me_reconnect_success_total 5630
telemt_me_reader_eof_total 5840
telemt_me_idle_close_by_peer_total 5839
telemt_me_route_drop_no_conn_total 231860
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 165
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 828
telemt_desync_full_logged_total 301
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 350
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 5843
telemt_me_writer_restored_same_endpoint_total 5609
telemt_me_writer_removed_unexpected_minus_restored_total 234
telemt_user_connections_total{user="hello"} 475174
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 7306209236 (6.80 GB)
telemt_user_octets_to_client{user="hello"} 156564455484 (145.81 GB)
telemt_user_unique_ips_current{user="hello"} 32
```