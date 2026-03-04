# Server Metrics 2026-03-04 22:09:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 4551.4 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52998
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 417
telemt_upstream_connect_attempt_total 2944
telemt_upstream_connect_success_total 2912
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2912
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 546
telemt_me_reconnect_success_total 558
telemt_me_reader_eof_total 553
telemt_me_idle_close_by_peer_total 553
telemt_me_route_drop_no_conn_total 13452
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 553
telemt_me_writer_restored_same_endpoint_total 538
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 44600
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 2170626484 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 20214210212 (18.83 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 4546.0 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19755
telemt_connections_bad_total 673
telemt_handshake_timeouts_total 119
telemt_upstream_connect_attempt_total 3125
telemt_upstream_connect_success_total 3093
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3093
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1315
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 569
telemt_me_reconnect_success_total 580
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 5593
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_restored_same_endpoint_total 561
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 18326
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 174740628 (166.65 MB)
telemt_user_octets_to_client{user="hello"} 4953728052 (4.61 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 4542.8 (1h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45092
telemt_connections_bad_total 746
telemt_handshake_timeouts_total 212
telemt_upstream_connect_attempt_total 1310
telemt_upstream_connect_success_total 1294
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 1294
telemt_upstream_connect_attempts_per_request{bucket="2"} 3
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 719
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 19
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 13508
telemt_me_single_endpoint_shadow_rotate_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 119
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 25
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 54
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 40924
telemt_user_connections_current{user="hello"} 299
telemt_user_octets_from_client{user="hello"} 636562368 (607.07 MB)
telemt_user_octets_to_client{user="hello"} 15907783500 (14.82 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 36590.8 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507309
telemt_connections_bad_total 66732
telemt_handshake_timeouts_total 14639
telemt_upstream_connect_attempt_total 15927
telemt_upstream_connect_success_total 15927
telemt_upstream_connect_attempts_per_request{bucket="1"} 15927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 2135
telemt_me_reconnect_success_total 2122
telemt_me_reader_eof_total 2162
telemt_me_idle_close_by_peer_total 2162
telemt_me_route_drop_no_conn_total 175641
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
telemt_me_writer_removed_unexpected_total 2163
telemt_me_writer_restored_same_endpoint_total 2098
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 397833
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 5634311452 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 153113359552 (142.60 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 36950.4 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509352
telemt_connections_bad_total 3758
telemt_handshake_timeouts_total 5662
telemt_upstream_connect_attempt_total 21722
telemt_upstream_connect_success_total 21608
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 21608
telemt_upstream_connect_attempts_per_request{bucket="2"} 47
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9191
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 309
telemt_me_reconnect_attempts_total 4560
telemt_me_reconnect_success_total 4548
telemt_me_reader_eof_total 4712
telemt_me_idle_close_by_peer_total 4712
telemt_me_route_drop_no_conn_total 225349
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 298
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4715
telemt_me_writer_restored_same_endpoint_total 4527
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 459835
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 7135021484 (6.65 GB)
telemt_user_octets_to_client{user="hello"} 147139970552 (137.03 GB)
telemt_user_unique_ips_current{user="hello"} 33
```