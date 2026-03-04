# Server Metrics 2026-03-04 03:30:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 22804.0 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145514
telemt_connections_bad_total 1533
telemt_handshake_timeouts_total 2418
telemt_upstream_connect_attempt_total 17569
telemt_upstream_connect_success_total 17494
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 17494
telemt_upstream_connect_attempts_per_request{bucket="2"} 33
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 184
telemt_me_reconnect_attempts_total 4258
telemt_me_reconnect_success_total 4247
telemt_me_reader_eof_total 4348
telemt_me_idle_close_by_peer_total 4348
telemt_me_route_drop_no_conn_total 50418
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 286
telemt_desync_full_logged_total 103
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 4
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 4348
telemt_me_writer_restored_same_endpoint_total 4227
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 138269
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 1303168424 (1.21 GB)
telemt_user_octets_to_client{user="hello"} 41836126684 (38.96 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 22800.7 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68643
telemt_connections_bad_total 281
telemt_handshake_timeouts_total 17634
telemt_upstream_connect_attempt_total 57824
telemt_upstream_connect_success_total 57244
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 57238
telemt_upstream_connect_attempts_per_request{bucket="2"} 279
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_keepalive_timeout_total 911
telemt_me_reconnect_attempts_total 36502
telemt_me_reconnect_success_total 36479
telemt_me_reader_eof_total 37405
telemt_me_idle_close_by_peer_total 37404
telemt_me_route_drop_no_conn_total 22272
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 154
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 37466
telemt_me_writer_restored_same_endpoint_total 36459
telemt_me_writer_removed_unexpected_minus_restored_total 1007
telemt_user_connections_total{user="hello"} 49904
telemt_user_connections_current{user="hello"} 223
telemt_user_octets_from_client{user="hello"} 413975696 (394.80 MB)
telemt_user_octets_to_client{user="hello"} 25503045000 (23.75 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 22799.5 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 158896
telemt_connections_bad_total 58036
telemt_handshake_timeouts_total 3589
telemt_upstream_connect_attempt_total 30828
telemt_upstream_connect_success_total 30616
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 30616
telemt_upstream_connect_attempts_per_request{bucket="2"} 98
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17917
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12602
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 97
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 12563
telemt_me_reconnect_success_total 12535
telemt_me_reader_eof_total 13182
telemt_me_idle_close_by_peer_total 13179
telemt_me_route_drop_no_conn_total 30775
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 295
telemt_desync_full_logged_total 102
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 2
telemt_pool_force_close_total 63
telemt_me_writer_removed_unexpected_total 13187
telemt_me_writer_restored_same_endpoint_total 12514
telemt_me_writer_removed_unexpected_minus_restored_total 673
telemt_user_connections_total{user="hello"} 93784
telemt_user_connections_current{user="hello"} 191
telemt_user_octets_from_client{user="hello"} 584715284 (557.63 MB)
telemt_user_octets_to_client{user="hello"} 24421320724 (22.74 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 22798.4 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75899
telemt_connections_bad_total 1369
telemt_handshake_timeouts_total 687
telemt_upstream_connect_attempt_total 14551
telemt_upstream_connect_success_total 14478
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 14478
telemt_upstream_connect_attempts_per_request{bucket="2"} 36
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5522
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 149
telemt_me_reconnect_attempts_total 1980
telemt_me_reconnect_success_total 1983
telemt_me_reader_eof_total 1992
telemt_me_idle_close_by_peer_total 1992
telemt_me_route_drop_no_conn_total 25249
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 97
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 7
telemt_pool_force_close_total 157
telemt_me_writer_removed_unexpected_total 1992
telemt_me_writer_restored_same_endpoint_total 1962
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 70577
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 635528108 (606.09 MB)
telemt_user_octets_to_client{user="hello"} 24891731884 (23.18 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 22797.0 (6h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173487
telemt_connections_bad_total 119
telemt_handshake_timeouts_total 79351
telemt_upstream_connect_attempt_total 34698
telemt_upstream_connect_success_total 34477
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 34477
telemt_upstream_connect_attempts_per_request{bucket="2"} 103
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20184
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 473
telemt_me_reconnect_attempts_total 17408
telemt_me_reconnect_success_total 17401
telemt_me_reader_eof_total 18444
telemt_me_idle_close_by_peer_total 18443
telemt_me_route_drop_no_conn_total 45529
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 123
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 92
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_pool_swap_total 2
telemt_pool_force_close_total 60
telemt_pool_stale_pick_total 2654
telemt_me_writer_removed_unexpected_total 18454
telemt_me_writer_restored_same_endpoint_total 17377
telemt_me_writer_removed_unexpected_minus_restored_total 1077
telemt_user_connections_total{user="hello"} 90714
telemt_user_connections_current{user="hello"} 192
telemt_user_octets_from_client{user="hello"} 536179032 (511.34 MB)
telemt_user_octets_to_client{user="hello"} 20753461392 (19.33 GB)
telemt_user_unique_ips_current{user="hello"} 24
```