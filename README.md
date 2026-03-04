# Server Metrics 2026-03-04 15:33:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 66163.7 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1242603
telemt_connections_bad_total 15967
telemt_handshake_timeouts_total 22340
telemt_upstream_connect_attempt_total 38473
telemt_upstream_connect_success_total 38300
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 38300
telemt_upstream_connect_attempts_per_request{bucket="2"} 68
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 441
telemt_me_reconnect_attempts_total 8197
telemt_me_reconnect_success_total 8134
telemt_me_reader_eof_total 8399
telemt_me_idle_close_by_peer_total 8398
telemt_me_route_drop_no_conn_total 457687
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2465
telemt_desync_full_logged_total 799
telemt_desync_suppressed_total 1666
telemt_desync_frames_bucket_total{bucket="1_2"} 732
telemt_desync_frames_bucket_total{bucket="3_10"} 925
telemt_desync_frames_bucket_total{bucket="gt_10"} 808
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8399
telemt_me_writer_restored_same_endpoint_total 8112
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 1002782
telemt_user_connections_current{user="hello"} 1129
telemt_user_octets_from_client{user="hello"} 13371152632 (12.45 GB)
telemt_user_octets_to_client{user="hello"} 338338549420 (315.10 GB)
telemt_user_unique_ips_current{user="hello"} 87
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 66159.9 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 471356
telemt_connections_bad_total 4154
telemt_handshake_timeouts_total 30444
telemt_upstream_connect_attempt_total 120296
telemt_upstream_connect_success_total 118578
telemt_upstream_connect_fail_total 821
telemt_upstream_connect_attempts_per_request{bucket="1"} 118572
telemt_upstream_connect_attempts_per_request{bucket="2"} 827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 77028
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41526
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 821
telemt_me_keepalive_timeout_total 1577
telemt_me_reconnect_attempts_total 65738
telemt_me_reconnect_success_total 65633
telemt_me_reader_eof_total 67339
telemt_me_idle_close_by_peer_total 67338
telemt_me_route_drop_no_conn_total 191638
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 278
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1118
telemt_desync_full_logged_total 342
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 214
telemt_desync_frames_bucket_total{bucket="3_10"} 448
telemt_desync_frames_bucket_total{bucket="gt_10"} 456
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 67419
telemt_me_writer_restored_same_endpoint_total 65608
telemt_me_writer_removed_unexpected_minus_restored_total 1811
telemt_user_connections_total{user="hello"} 373560
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 5810891596 (5.41 GB)
telemt_user_octets_to_client{user="hello"} 118485753980 (110.35 GB)
telemt_user_unique_ips_current{user="hello"} 40
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 66158.9 (18h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 954113
telemt_connections_bad_total 196062
telemt_handshake_timeouts_total 30110
telemt_upstream_connect_attempt_total 87737
telemt_upstream_connect_success_total 87153
telemt_upstream_connect_fail_total 282
telemt_upstream_connect_attempts_per_request{bucket="1"} 87152
telemt_upstream_connect_attempts_per_request{bucket="2"} 283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 282
telemt_me_keepalive_timeout_total 1138
telemt_me_reconnect_attempts_total 39259
telemt_me_reconnect_success_total 39157
telemt_me_reader_eof_total 41210
telemt_me_idle_close_by_peer_total 41205
telemt_me_route_drop_no_conn_total 346099
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 273
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2008
telemt_desync_full_logged_total 664
telemt_desync_suppressed_total 1344
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 747
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 41222
telemt_me_writer_restored_same_endpoint_total 39135
telemt_me_writer_removed_unexpected_minus_restored_total 2087
telemt_user_connections_total{user="hello"} 682445
telemt_user_connections_current{user="hello"} 751
telemt_user_octets_from_client{user="hello"} 13842904980 (12.89 GB)
telemt_user_octets_to_client{user="hello"} 231471457224 (215.57 GB)
telemt_user_unique_ips_current{user="hello"} 64
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 12836.1 (3h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198987
telemt_connections_bad_total 19762
telemt_handshake_timeouts_total 5872
telemt_upstream_connect_attempt_total 5339
telemt_upstream_connect_success_total 5339
telemt_upstream_connect_attempts_per_request{bucket="1"} 5339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2181
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 858
telemt_me_reconnect_success_total 869
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_route_drop_no_conn_total 61794
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 214
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 135
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 877
telemt_me_writer_restored_same_endpoint_total 848
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 166472
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 2081490704 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 68758332048 (64.04 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 13195.5 (3h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224577
telemt_connections_bad_total 2502
telemt_handshake_timeouts_total 3514
telemt_upstream_connect_attempt_total 6815
telemt_upstream_connect_success_total 6784
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6784
telemt_upstream_connect_attempts_per_request{bucket="2"} 15
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 1285
telemt_me_reconnect_success_total 1293
telemt_me_reader_eof_total 1319
telemt_me_idle_close_by_peer_total 1319
telemt_me_route_drop_no_conn_total 84788
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 510
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 3
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1319
telemt_me_writer_restored_same_endpoint_total 1273
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 194451
telemt_user_connections_current{user="hello"} 600
telemt_user_octets_from_client{user="hello"} 3183462092 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 56385152656 (52.51 GB)
telemt_user_unique_ips_current{user="hello"} 59
```