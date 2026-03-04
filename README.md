# Server Metrics 2026-03-04 12:13:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 54170.7 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 913264
telemt_connections_bad_total 12091
telemt_handshake_timeouts_total 13821
telemt_upstream_connect_attempt_total 32805
telemt_upstream_connect_success_total 32664
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32664
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14597
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 7088
telemt_me_reconnect_success_total 7040
telemt_me_reader_eof_total 7260
telemt_me_idle_close_by_peer_total 7260
telemt_me_route_drop_no_conn_total 337259
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1493
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 990
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 571
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 15
telemt_pool_force_close_total 543
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7260
telemt_me_writer_restored_same_endpoint_total 7019
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 724109
telemt_user_connections_current{user="hello"} 841
telemt_user_octets_from_client{user="hello"} 7763810212 (7.23 GB)
telemt_user_octets_to_client{user="hello"} 222067216540 (206.82 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 54167.2 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 362123
telemt_connections_bad_total 3144
telemt_handshake_timeouts_total 27749
telemt_upstream_connect_attempt_total 101459
telemt_upstream_connect_success_total 99891
telemt_upstream_connect_fail_total 745
telemt_upstream_connect_attempts_per_request{bucket="1"} 99885
telemt_upstream_connect_attempts_per_request{bucket="2"} 751
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66781
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 745
telemt_me_keepalive_timeout_total 1408
telemt_me_reconnect_attempts_total 56971
telemt_me_reconnect_success_total 56883
telemt_me_reader_eof_total 58320
telemt_me_idle_close_by_peer_total 58319
telemt_me_route_drop_no_conn_total 148732
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 227
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58400
telemt_me_writer_restored_same_endpoint_total 56858
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 272195
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 3583393024 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 86108012496 (80.19 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 54166.0 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 688729
telemt_connections_bad_total 161997
telemt_handshake_timeouts_total 22561
telemt_upstream_connect_attempt_total 79546
telemt_upstream_connect_success_total 79076
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 79075
telemt_upstream_connect_attempts_per_request{bucket="2"} 226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32390
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 1034
telemt_me_reconnect_attempts_total 37131
telemt_me_reconnect_success_total 37039
telemt_me_reader_eof_total 39014
telemt_me_idle_close_by_peer_total 39010
telemt_me_route_drop_no_conn_total 257396
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1216
telemt_desync_full_logged_total 435
telemt_desync_suppressed_total 781
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 411
telemt_desync_frames_bucket_total{bucket="gt_10"} 454
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 39026
telemt_me_writer_restored_same_endpoint_total 37017
telemt_me_writer_removed_unexpected_minus_restored_total 2009
telemt_user_connections_total{user="hello"} 478936
telemt_user_connections_current{user="hello"} 577
telemt_user_octets_from_client{user="hello"} 11303987732 (10.53 GB)
telemt_user_octets_to_client{user="hello"} 160022668548 (149.03 GB)
telemt_user_unique_ips_current{user="hello"} 56
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 843.3 (0h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9749
telemt_connections_bad_total 823
telemt_handshake_timeouts_total 231
telemt_upstream_connect_attempt_total 224
telemt_upstream_connect_success_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 72
telemt_me_reconnect_attempts_total 4
telemt_me_reconnect_success_total 24
telemt_me_reader_eof_total 4
telemt_me_idle_close_by_peer_total 4
telemt_me_route_drop_no_conn_total 3443
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 6
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 4
telemt_me_writer_restored_same_endpoint_total 3
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 8516
telemt_user_connections_current{user="hello"} 451
telemt_user_octets_from_client{user="hello"} 116637036 (111.23 MB)
telemt_user_octets_to_client{user="hello"} 6313263968 (5.88 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 1202.8 (0h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20472
telemt_connections_bad_total 1
telemt_handshake_timeouts_total 328
telemt_upstream_connect_attempt_total 260
telemt_upstream_connect_success_total 255
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 255
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 132
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 6
telemt_me_reconnect_success_total 22
telemt_me_reader_eof_total 2
telemt_me_idle_close_by_peer_total 2
telemt_me_route_drop_no_conn_total 6242
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 56
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 16
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 2
telemt_me_writer_restored_same_endpoint_total 2
telemt_user_connections_total{user="hello"} 17872
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 192518488 (183.60 MB)
telemt_user_octets_to_client{user="hello"} 5742411488 (5.35 GB)
telemt_user_unique_ips_current{user="hello"} 46
```