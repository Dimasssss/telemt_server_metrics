# Server Metrics 2026-03-04 13:30:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 58784.2 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1049394
telemt_connections_bad_total 13900
telemt_handshake_timeouts_total 16954
telemt_upstream_connect_attempt_total 34752
telemt_upstream_connect_success_total 34596
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 34596
telemt_upstream_connect_attempts_per_request{bucket="2"} 63
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15456
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 388
telemt_me_reconnect_attempts_total 7253
telemt_me_reconnect_success_total 7199
telemt_me_reader_eof_total 7423
telemt_me_idle_close_by_peer_total 7422
telemt_me_route_drop_no_conn_total 375732
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 232
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1720
telemt_desync_full_logged_total 579
telemt_desync_suppressed_total 1141
telemt_desync_frames_bucket_total{bucket="1_2"} 479
telemt_desync_frames_bucket_total{bucket="3_10"} 654
telemt_desync_frames_bucket_total{bucket="gt_10"} 587
telemt_pool_swap_total 15
telemt_pool_force_close_total 576
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7423
telemt_me_writer_restored_same_endpoint_total 7177
telemt_me_writer_removed_unexpected_minus_restored_total 246
telemt_user_connections_total{user="hello"} 826895
telemt_user_connections_current{user="hello"} 1197
telemt_user_octets_from_client{user="hello"} 9375746584 (8.73 GB)
telemt_user_octets_to_client{user="hello"} 278418155652 (259.30 GB)
telemt_user_unique_ips_current{user="hello"} 101
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 58780.8 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407669
telemt_connections_bad_total 3414
telemt_handshake_timeouts_total 29029
telemt_upstream_connect_attempt_total 105768
telemt_upstream_connect_success_total 104160
telemt_upstream_connect_fail_total 766
telemt_upstream_connect_attempts_per_request{bucket="1"} 104154
telemt_upstream_connect_attempts_per_request{bucket="2"} 772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35084
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 766
telemt_me_keepalive_timeout_total 1437
telemt_me_reconnect_attempts_total 58218
telemt_me_reconnect_success_total 58125
telemt_me_reader_eof_total 59595
telemt_me_idle_close_by_peer_total 59594
telemt_me_route_drop_no_conn_total 165048
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 247
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 806
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 558
telemt_desync_frames_bucket_total{bucket="1_2"} 156
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 59675
telemt_me_writer_restored_same_endpoint_total 58100
telemt_me_writer_removed_unexpected_minus_restored_total 1575
telemt_user_connections_total{user="hello"} 313443
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 4071711620 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 99336492804 (92.51 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 58779.7 (16h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 793368
telemt_connections_bad_total 174950
telemt_handshake_timeouts_total 27910
telemt_upstream_connect_attempt_total 82473
telemt_upstream_connect_success_total 81956
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 81955
telemt_upstream_connect_attempts_per_request{bucket="2"} 250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 48330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33404
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 222
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1072
telemt_me_reconnect_attempts_total 37805
telemt_me_reconnect_success_total 37709
telemt_me_reader_eof_total 39699
telemt_me_idle_close_by_peer_total 39695
telemt_me_route_drop_no_conn_total 291727
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_shadow_rotate_total 245
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1497
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 981
telemt_desync_frames_bucket_total{bucket="1_2"} 464
telemt_desync_frames_bucket_total{bucket="3_10"} 492
telemt_desync_frames_bucket_total{bucket="gt_10"} 541
telemt_pool_swap_total 6
telemt_pool_force_close_total 331
telemt_me_writer_removed_unexpected_total 39711
telemt_me_writer_restored_same_endpoint_total 37687
telemt_me_writer_removed_unexpected_minus_restored_total 2024
telemt_user_connections_total{user="hello"} 553817
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 12048544404 (11.22 GB)
telemt_user_octets_to_client{user="hello"} 185456568752 (172.72 GB)
telemt_user_unique_ips_current{user="hello"} 74
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 5456.9 (1h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67259
telemt_connections_bad_total 6404
telemt_handshake_timeouts_total 1085
telemt_upstream_connect_attempt_total 2107
telemt_upstream_connect_success_total 2107
telemt_upstream_connect_attempts_per_request{bucket="1"} 2107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 798
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 171
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 170
telemt_me_idle_close_by_peer_total 170
telemt_me_route_drop_no_conn_total 23510
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 170
telemt_me_writer_restored_same_endpoint_total 167
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 58796
telemt_user_connections_current{user="hello"} 534
telemt_user_octets_from_client{user="hello"} 1099208428 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 39293971132 (36.60 GB)
telemt_user_unique_ips_current{user="hello"} 59
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 5816.1 (1h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105545
telemt_connections_bad_total 513
telemt_handshake_timeouts_total 1634
telemt_upstream_connect_attempt_total 3716
telemt_upstream_connect_success_total 3701
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 3701
telemt_upstream_connect_attempts_per_request{bucket="2"} 7
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2259
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 772
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 34734
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 278
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 172
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 786
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 90683
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 961515492 (916.97 MB)
telemt_user_octets_to_client{user="hello"} 24667609876 (22.97 GB)
telemt_user_unique_ips_current{user="hello"} 60
```