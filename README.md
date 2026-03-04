# Server Metrics 2026-03-04 13:35:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 59092.5 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1056984
telemt_connections_bad_total 13901
telemt_handshake_timeouts_total 17315
telemt_upstream_connect_attempt_total 34949
telemt_upstream_connect_success_total 34793
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 34793
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19191
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 390
telemt_me_reconnect_attempts_total 7310
telemt_me_reconnect_success_total 7256
telemt_me_reader_eof_total 7481
telemt_me_idle_close_by_peer_total 7480
telemt_me_route_drop_no_conn_total 378231
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1728
telemt_desync_full_logged_total 582
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 482
telemt_desync_frames_bucket_total{bucket="3_10"} 655
telemt_desync_frames_bucket_total{bucket="gt_10"} 591
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7481
telemt_me_writer_restored_same_endpoint_total 7234
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 833875
telemt_user_connections_current{user="hello"} 1192
telemt_user_octets_from_client{user="hello"} 9457853484 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 280935197144 (261.64 GB)
telemt_user_unique_ips_current{user="hello"} 113
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 59089.0 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 410239
telemt_connections_bad_total 3475
telemt_handshake_timeouts_total 29066
telemt_upstream_connect_attempt_total 106222
telemt_upstream_connect_success_total 104614
telemt_upstream_connect_fail_total 766
telemt_upstream_connect_attempts_per_request{bucket="1"} 104608
telemt_upstream_connect_attempts_per_request{bucket="2"} 772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35329
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 766
telemt_me_keepalive_timeout_total 1442
telemt_me_reconnect_attempts_total 58446
telemt_me_reconnect_success_total 58352
telemt_me_reader_eof_total 59840
telemt_me_idle_close_by_peer_total 59839
telemt_me_route_drop_no_conn_total 165957
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 808
telemt_desync_full_logged_total 249
telemt_desync_suppressed_total 559
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 59920
telemt_me_writer_restored_same_endpoint_total 58327
telemt_me_writer_removed_unexpected_minus_restored_total 1593
telemt_user_connections_total{user="hello"} 315812
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 4102256268 (3.82 GB)
telemt_user_octets_to_client{user="hello"} 100428328056 (93.53 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 59087.9 (16h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 799613
telemt_connections_bad_total 175805
telemt_handshake_timeouts_total 28250
telemt_upstream_connect_attempt_total 82688
telemt_upstream_connect_success_total 82171
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 82170
telemt_upstream_connect_attempts_per_request{bucket="2"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1075
telemt_me_reconnect_attempts_total 37865
telemt_me_reconnect_success_total 37768
telemt_me_reader_eof_total 39760
telemt_me_idle_close_by_peer_total 39756
telemt_me_route_drop_no_conn_total 294182
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1520
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 997
telemt_desync_frames_bucket_total{bucket="1_2"} 473
telemt_desync_frames_bucket_total{bucket="3_10"} 501
telemt_desync_frames_bucket_total{bucket="gt_10"} 546
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39772
telemt_me_writer_restored_same_endpoint_total 37746
telemt_me_writer_removed_unexpected_minus_restored_total 2026
telemt_user_connections_total{user="hello"} 558639
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 12101299300 (11.27 GB)
telemt_user_octets_to_client{user="hello"} 188266651520 (175.34 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 5765.1 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70831
telemt_connections_bad_total 6683
telemt_handshake_timeouts_total 1118
telemt_upstream_connect_attempt_total 2301
telemt_upstream_connect_success_total 2301
telemt_upstream_connect_attempts_per_request{bucket="1"} 2301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 876
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 207
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 209
telemt_me_idle_close_by_peer_total 209
telemt_me_route_drop_no_conn_total 24732
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 81
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 45
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 209
telemt_me_writer_restored_same_endpoint_total 202
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 62001
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 1122121744 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 41001415628 (38.19 GB)
telemt_user_unique_ips_current{user="hello"} 62
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 6124.3 (1h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110508
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 1812
telemt_upstream_connect_attempt_total 4178
telemt_upstream_connect_success_total 4163
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 4163
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 991
telemt_me_reconnect_success_total 1002
telemt_me_reader_eof_total 1013
telemt_me_idle_close_by_peer_total 1013
telemt_me_route_drop_no_conn_total 37200
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 290
telemt_desync_full_logged_total 110
telemt_desync_suppressed_total 180
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 135
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 1013
telemt_me_writer_restored_same_endpoint_total 982
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 95095
telemt_user_connections_current{user="hello"} 504
telemt_user_octets_from_client{user="hello"} 1008469776 (961.75 MB)
telemt_user_octets_to_client{user="hello"} 26126747424 (24.33 GB)
telemt_user_unique_ips_current{user="hello"} 49
```