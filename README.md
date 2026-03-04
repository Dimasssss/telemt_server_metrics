# Server Metrics 2026-03-04 05:23:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 29561.0 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 218652
telemt_connections_bad_total 2306
telemt_handshake_timeouts_total 4321
telemt_upstream_connect_attempt_total 20627
telemt_upstream_connect_success_total 20534
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20534
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11661
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8845
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 4582
telemt_me_reconnect_success_total 4563
telemt_me_reader_eof_total 4668
telemt_me_idle_close_by_peer_total 4668
telemt_me_route_drop_no_conn_total 70966
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 581
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 367
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 6
telemt_pool_force_close_total 218
telemt_me_writer_removed_unexpected_total 4668
telemt_me_writer_restored_same_endpoint_total 4543
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 206623
telemt_user_connections_current{user="hello"} 670
telemt_user_octets_from_client{user="hello"} 2161169052 (2.01 GB)
telemt_user_octets_to_client{user="hello"} 68947487892 (64.21 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 29557.4 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102964
telemt_connections_bad_total 353
telemt_handshake_timeouts_total 21580
telemt_upstream_connect_attempt_total 66578
telemt_upstream_connect_success_total 65813
telemt_upstream_connect_fail_total 366
telemt_upstream_connect_attempts_per_request{bucket="1"} 65807
telemt_upstream_connect_attempts_per_request{bucket="2"} 372
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21141
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 366
telemt_me_keepalive_timeout_total 995
telemt_me_reconnect_attempts_total 40236
telemt_me_reconnect_success_total 40208
telemt_me_reader_eof_total 41213
telemt_me_idle_close_by_peer_total 41212
telemt_me_route_drop_no_conn_total 32291
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 212
telemt_desync_full_logged_total 88
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 41274
telemt_me_writer_restored_same_endpoint_total 40187
telemt_me_writer_removed_unexpected_minus_restored_total 1087
telemt_user_connections_total{user="hello"} 75226
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 669732924 (638.71 MB)
telemt_user_octets_to_client{user="hello"} 31786314460 (29.60 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 29556.3 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 230150
telemt_connections_bad_total 84622
telemt_handshake_timeouts_total 4854
telemt_upstream_connect_attempt_total 38783
telemt_upstream_connect_success_total 38532
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 38532
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22621
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 509
telemt_me_reconnect_attempts_total 15594
telemt_me_reconnect_success_total 15552
telemt_me_reader_eof_total 16381
telemt_me_idle_close_by_peer_total 16378
telemt_me_route_drop_no_conn_total 47116
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 125
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 338
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 16389
telemt_me_writer_restored_same_endpoint_total 15531
telemt_me_writer_removed_unexpected_minus_restored_total 858
telemt_user_connections_total{user="hello"} 136216
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 984564920 (938.95 MB)
telemt_user_octets_to_client{user="hello"} 35532051132 (33.09 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 29555.2 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115397
telemt_connections_bad_total 8045
telemt_handshake_timeouts_total 1456
telemt_upstream_connect_attempt_total 21099
telemt_upstream_connect_success_total 21010
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 21010
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13089
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7920
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 217
telemt_me_reconnect_attempts_total 3682
telemt_me_reconnect_success_total 3680
telemt_me_reader_eof_total 3720
telemt_me_idle_close_by_peer_total 3720
telemt_me_route_drop_no_conn_total 36172
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 123
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 3720
telemt_me_writer_restored_same_endpoint_total 3659
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 101277
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 885633160 (844.61 MB)
telemt_user_octets_to_client{user="hello"} 36321224408 (33.83 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 29553.8 (8h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246661
telemt_connections_bad_total 5432
telemt_handshake_timeouts_total 110726
telemt_upstream_connect_attempt_total 43775
telemt_upstream_connect_success_total 43484
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 43484
telemt_upstream_connect_attempts_per_request{bucket="2"} 136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17617
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 596
telemt_me_reconnect_attempts_total 21089
telemt_me_reconnect_success_total 21078
telemt_me_reader_eof_total 22253
telemt_me_idle_close_by_peer_total 22252
telemt_me_route_drop_no_conn_total 56911
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 126
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 181
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 3
telemt_pool_force_close_total 87
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22266
telemt_me_writer_restored_same_endpoint_total 21054
telemt_me_writer_removed_unexpected_minus_restored_total 1212
telemt_user_connections_total{user="hello"} 126157
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 1014730464 (967.72 MB)
telemt_user_octets_to_client{user="hello"} 29154009648 (27.15 GB)
telemt_user_unique_ips_current{user="hello"} 24
```