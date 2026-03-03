# Server Metrics 2026-03-03 23:25:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 8063.4 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64075
telemt_connections_bad_total 647
telemt_handshake_timeouts_total 211
telemt_upstream_connect_attempt_total 4705
telemt_upstream_connect_success_total 4680
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 4680
telemt_upstream_connect_attempts_per_request{bucket="2"} 9
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2036
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 593
telemt_me_reconnect_success_total 604
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 25094
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 110
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 71
telemt_desync_frames_bucket_total{bucket="1_2"} 30
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 592
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 61913
telemt_user_connections_current{user="hello"} 368
telemt_user_octets_from_client{user="hello"} 533579292 (508.86 MB)
telemt_user_octets_to_client{user="hello"} 19646384832 (18.30 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 8060.0 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30022
telemt_connections_bad_total 18
telemt_handshake_timeouts_total 6063
telemt_upstream_connect_attempt_total 11125
telemt_upstream_connect_success_total 10948
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 10948
telemt_upstream_connect_attempts_per_request{bucket="2"} 86
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3906
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 4897
telemt_me_reconnect_success_total 4908
telemt_me_reader_eof_total 4980
telemt_me_idle_close_by_peer_total 4979
telemt_me_route_drop_no_conn_total 11499
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 4980
telemt_me_writer_restored_same_endpoint_total 4888
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 23568
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 149951556 (143.00 MB)
telemt_user_octets_to_client{user="hello"} 12086060624 (11.26 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 8058.7 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70481
telemt_connections_bad_total 20158
telemt_handshake_timeouts_total 1756
telemt_upstream_connect_attempt_total 9728
telemt_upstream_connect_success_total 9680
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 9680
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4052
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 3669
telemt_me_reconnect_success_total 3674
telemt_me_reader_eof_total 3826
telemt_me_idle_close_by_peer_total 3825
telemt_me_route_drop_no_conn_total 15435
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 145
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 46
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 3827
telemt_me_writer_restored_same_endpoint_total 3653
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 47417
telemt_user_connections_current{user="hello"} 145
telemt_user_octets_from_client{user="hello"} 314600848 (300.03 MB)
telemt_user_octets_to_client{user="hello"} 13331148624 (12.42 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 8057.8 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32036
telemt_connections_bad_total 107
telemt_handshake_timeouts_total 484
telemt_upstream_connect_attempt_total 4376
telemt_upstream_connect_success_total 4353
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 4353
telemt_upstream_connect_attempts_per_request{bucket="2"} 11
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 374
telemt_me_reconnect_success_total 388
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 12089
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 2
telemt_pool_force_close_total 67
telemt_me_writer_removed_unexpected_total 372
telemt_me_writer_restored_same_endpoint_total 369
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 31025
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 227928196 (217.37 MB)
telemt_user_octets_to_client{user="hello"} 9557809388 (8.90 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 8056.4 (2h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73996
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 28685
telemt_upstream_connect_attempt_total 5791
telemt_upstream_connect_success_total 5733
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5733
telemt_upstream_connect_attempts_per_request{bucket="2"} 27
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2227
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 1447
telemt_me_reconnect_success_total 1462
telemt_me_reader_eof_total 1499
telemt_me_idle_close_by_peer_total 1499
telemt_me_route_drop_no_conn_total 31891
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 39
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 1501
telemt_me_writer_restored_same_endpoint_total 1438
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 43959
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 220982860 (210.75 MB)
telemt_user_octets_to_client{user="hello"} 12359507728 (11.51 GB)
telemt_user_unique_ips_current{user="hello"} 20
```