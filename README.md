# Server Metrics 2026-03-04 16:34:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 69852.0 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1347572
telemt_connections_bad_total 18600
telemt_handshake_timeouts_total 23023
telemt_upstream_connect_attempt_total 41110
telemt_upstream_connect_success_total 40923
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 40923
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22511
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18328
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 49
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 466
telemt_me_reconnect_attempts_total 8935
telemt_me_reconnect_success_total 8865
telemt_me_reader_eof_total 9167
telemt_me_idle_close_by_peer_total 9166
telemt_me_route_drop_no_conn_total 530321
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 273
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2898
telemt_desync_full_logged_total 920
telemt_desync_suppressed_total 1978
telemt_desync_frames_bucket_total{bucket="1_2"} 838
telemt_desync_frames_bucket_total{bucket="3_10"} 1083
telemt_desync_frames_bucket_total{bucket="gt_10"} 977
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 9168
telemt_me_writer_restored_same_endpoint_total 8843
telemt_me_writer_removed_unexpected_minus_restored_total 325
telemt_user_connections_total{user="hello"} 1098980
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 14630738716 (13.63 GB)
telemt_user_octets_to_client{user="hello"} 367305586432 (342.08 GB)
telemt_user_unique_ips_current{user="hello"} 111
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 69848.4 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 514592
telemt_connections_bad_total 5641
telemt_handshake_timeouts_total 30759
telemt_upstream_connect_attempt_total 124460
telemt_upstream_connect_success_total 122667
telemt_upstream_connect_fail_total 858
telemt_upstream_connect_attempts_per_request{bucket="1"} 122661
telemt_upstream_connect_attempts_per_request{bucket="2"} 864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 858
telemt_me_keepalive_timeout_total 1635
telemt_me_reconnect_attempts_total 67709
telemt_me_reconnect_success_total 67602
telemt_me_reader_eof_total 69339
telemt_me_idle_close_by_peer_total 69338
telemt_me_route_drop_no_conn_total 214829
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 292
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1322
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 919
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 520
telemt_desync_frames_bucket_total{bucket="gt_10"} 555
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 171
telemt_me_writer_removed_unexpected_total 69419
telemt_me_writer_restored_same_endpoint_total 67576
telemt_me_writer_removed_unexpected_minus_restored_total 1843
telemt_user_connections_total{user="hello"} 413459
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 6147457740 (5.73 GB)
telemt_user_octets_to_client{user="hello"} 130006624224 (121.08 GB)
telemt_user_unique_ips_current{user="hello"} 36
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 69847.3 (19h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1035998
telemt_connections_bad_total 206699
telemt_handshake_timeouts_total 30374
telemt_upstream_connect_attempt_total 90606
telemt_upstream_connect_success_total 89982
telemt_upstream_connect_fail_total 302
telemt_upstream_connect_attempts_per_request{bucket="1"} 89981
telemt_upstream_connect_attempts_per_request{bucket="2"} 303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36708
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 240
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 302
telemt_me_keepalive_timeout_total 1182
telemt_me_reconnect_attempts_total 40248
telemt_me_reconnect_success_total 40141
telemt_me_reader_eof_total 42265
telemt_me_idle_close_by_peer_total 42260
telemt_me_route_drop_no_conn_total 384536
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 287
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2172
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1453
telemt_desync_frames_bucket_total{bucket="1_2"} 640
telemt_desync_frames_bucket_total{bucket="3_10"} 712
telemt_desync_frames_bucket_total{bucket="gt_10"} 820
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42278
telemt_me_writer_restored_same_endpoint_total 40119
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 749880
telemt_user_connections_current{user="hello"} 636
telemt_user_octets_from_client{user="hello"} 14580830272 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 256854265244 (239.21 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 16524.5 (4h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270823
telemt_connections_bad_total 33516
telemt_handshake_timeouts_total 6505
telemt_upstream_connect_attempt_total 6498
telemt_upstream_connect_success_total 6498
telemt_upstream_connect_attempts_per_request{bucket="1"} 6498
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3643
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2855
telemt_me_keepalive_timeout_total 77
telemt_me_reconnect_attempts_total 876
telemt_me_reconnect_success_total 883
telemt_me_reader_eof_total 893
telemt_me_idle_close_by_peer_total 893
telemt_me_route_drop_no_conn_total 90291
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 283
telemt_desync_full_logged_total 107
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 5
telemt_pool_force_close_total 189
telemt_me_writer_removed_unexpected_total 893
telemt_me_writer_restored_same_endpoint_total 862
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 221457
telemt_user_connections_current{user="hello"} 444
telemt_user_octets_from_client{user="hello"} 2853667488 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 83242992924 (77.53 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 16883.9 (4h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288611
telemt_connections_bad_total 3076
telemt_handshake_timeouts_total 4092
telemt_upstream_connect_attempt_total 8161
telemt_upstream_connect_success_total 8120
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 8120
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4692
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 1354
telemt_me_reader_eof_total 1381
telemt_me_idle_close_by_peer_total 1381
telemt_me_route_drop_no_conn_total 112631
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 546
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 332
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1381
telemt_me_writer_restored_same_endpoint_total 1333
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 248843
telemt_user_connections_current{user="hello"} 592
telemt_user_octets_from_client{user="hello"} 4141477644 (3.86 GB)
telemt_user_octets_to_client{user="hello"} 73727176504 (68.66 GB)
telemt_user_unique_ips_current{user="hello"} 52
```