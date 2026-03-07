# Server Metrics 2026-03-07 01:21:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 25985.0 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314339
telemt_connections_bad_total 3694
telemt_handshake_timeouts_total 9456
telemt_upstream_connect_attempt_total 79443
telemt_upstream_connect_success_total 77263
telemt_upstream_connect_fail_total 2042
telemt_upstream_connect_attempts_per_request{bucket="1"} 79305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29128
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47893
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2042
telemt_me_keepalive_timeout_total 1729
telemt_me_reconnect_attempts_total 47693
telemt_me_reconnect_success_total 45716
telemt_me_reader_eof_total 47983
telemt_me_idle_close_by_peer_total 47983
telemt_me_route_drop_no_conn_total 118987
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1008
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 12
telemt_pool_force_close_total 570
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 48096
telemt_me_writer_restored_same_endpoint_total 45590
telemt_me_writer_restored_fallback_total 120
telemt_me_async_recovery_trigger_total 39491
telemt_me_writer_removed_unexpected_minus_restored_total 2386
telemt_user_connections_total{user="hello"} 285680
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 4342998792 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 124004799396 (115.49 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 25985.0 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135478
telemt_connections_bad_total 120
telemt_handshake_timeouts_total 16772
telemt_upstream_connect_attempt_total 159334
telemt_upstream_connect_success_total 159332
telemt_upstream_connect_attempts_per_request{bucket="1"} 159332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40346
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1298
telemt_me_reconnect_attempts_total 122022
telemt_me_reconnect_success_total 121717
telemt_me_reader_eof_total 110887
telemt_me_idle_close_by_peer_total 110882
telemt_me_route_drop_no_conn_total 43057
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 223
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 810
telemt_desync_full_logged_total 215
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 18
telemt_pool_force_close_total 1171
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 110917
telemt_me_writer_restored_same_endpoint_total 121715
telemt_me_async_recovery_trigger_total 39483
telemt_user_connections_total{user="hello"} 111967
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 1576925692 (1.47 GB)
telemt_user_octets_to_client{user="hello"} 38679771176 (36.02 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 25985.0 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243045
telemt_connections_bad_total 1261
telemt_handshake_timeouts_total 3596
telemt_upstream_connect_attempt_total 116270
telemt_upstream_connect_success_total 116081
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 116152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 76260
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 2291
telemt_me_reconnect_attempts_total 83986
telemt_me_reconnect_success_total 83911
telemt_me_reader_eof_total 86063
telemt_me_idle_close_by_peer_total 86058
telemt_me_route_drop_no_conn_total 91222
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 213
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1057
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 787
telemt_desync_frames_bucket_total{bucket="1_2"} 202
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 14
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 86234
telemt_me_writer_restored_same_endpoint_total 83904
telemt_me_async_recovery_trigger_total 118240
telemt_me_writer_removed_unexpected_minus_restored_total 2330
telemt_user_connections_total{user="hello"} 227328
telemt_user_connections_current{user="hello"} 165
telemt_user_octets_from_client{user="hello"} 21515399760 (20.04 GB)
telemt_user_octets_to_client{user="hello"} 64665857800 (60.22 GB)
telemt_user_unique_ips_current{user="hello"} 74
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 25985.2 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 249801
telemt_connections_bad_total 73543
telemt_handshake_timeouts_total 16945
telemt_upstream_connect_attempt_total 47737
telemt_upstream_connect_success_total 47650
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 47690
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28551
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 931
telemt_me_reconnect_attempts_total 15717
telemt_me_reconnect_success_total 15688
telemt_me_reader_eof_total 21522
telemt_me_idle_close_by_peer_total 21520
telemt_me_route_drop_no_conn_total 66665
telemt_me_single_endpoint_shadow_rotate_total 216
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 222
telemt_desync_full_logged_total 99
telemt_desync_suppressed_total 123
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 21527
telemt_me_writer_restored_same_endpoint_total 15683
telemt_me_writer_removed_unexpected_minus_restored_total 5844
telemt_user_connections_total{user="hello"} 155231
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 1745678824 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 50176088484 (46.73 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 25983.7 (7h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 213304
telemt_connections_bad_total 514
telemt_handshake_timeouts_total 2556
telemt_upstream_connect_attempt_total 43496
telemt_upstream_connect_success_total 43334
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 43354
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16957
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1203
telemt_me_reconnect_attempts_total 12921
telemt_me_reconnect_success_total 12886
telemt_me_reader_eof_total 17654
telemt_me_idle_close_by_peer_total 17652
telemt_me_route_drop_no_conn_total 71211
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 212
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 800
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 264
telemt_pool_swap_total 15
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 17722
telemt_me_writer_restored_same_endpoint_total 12878
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 4840
telemt_user_connections_total{user="hello"} 195843
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 10208018744 (9.51 GB)
telemt_user_octets_to_client{user="hello"} 68219777156 (63.53 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 21
```