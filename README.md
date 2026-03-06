# Server Metrics 2026-03-06 04:17:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 21376.3 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151529
telemt_connections_bad_total 15928
telemt_handshake_timeouts_total 2871
telemt_upstream_connect_attempt_total 23178
telemt_upstream_connect_success_total 23001
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 23001
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9000
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 253
telemt_me_reconnect_attempts_total 8683
telemt_me_reconnect_success_total 8654
telemt_me_reader_eof_total 8967
telemt_me_idle_close_by_peer_total 8967
telemt_me_route_drop_no_conn_total 42273
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 369
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 237
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8967
telemt_me_writer_restored_same_endpoint_total 8648
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 124927
telemt_user_connections_current{user="hello"} 528
telemt_user_octets_from_client{user="hello"} 2820627060 (2.63 GB)
telemt_user_octets_to_client{user="hello"} 48312737424 (44.99 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 21371.7 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 53502
telemt_connections_bad_total 122
telemt_handshake_timeouts_total 731
telemt_upstream_connect_attempt_total 19108
telemt_upstream_connect_success_total 19106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10815
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4484
telemt_me_reconnect_success_total 4468
telemt_me_reader_eof_total 4555
telemt_me_idle_close_by_peer_total 4555
telemt_me_route_drop_no_conn_total 15920
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 183
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 118
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4556
telemt_me_writer_restored_same_endpoint_total 4462
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 51659
telemt_user_connections_current{user="hello"} 220
telemt_user_octets_from_client{user="hello"} 417713788 (398.36 MB)
telemt_user_octets_to_client{user="hello"} 13031877820 (12.14 GB)
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 21369.2 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 91728
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 1670
telemt_upstream_connect_attempt_total 20024
telemt_upstream_connect_success_total 19856
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 19856
telemt_upstream_connect_attempts_per_request{bucket="2"} 75
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11803
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 6065
telemt_me_reconnect_success_total 6043
telemt_me_reader_eof_total 6318
telemt_me_idle_close_by_peer_total 6318
telemt_me_route_drop_no_conn_total 25952
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 180
telemt_desync_full_logged_total 55
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6322
telemt_me_writer_restored_same_endpoint_total 6035
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 86088
telemt_user_connections_current{user="hello"} 358
telemt_user_octets_from_client{user="hello"} 892209588 (850.88 MB)
telemt_user_octets_to_client{user="hello"} 29208632864 (27.20 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 21365.8 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77384
telemt_connections_bad_total 2605
telemt_handshake_timeouts_total 4494
telemt_upstream_connect_attempt_total 14266
telemt_upstream_connect_success_total 14219
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 14219
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5874
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2788
telemt_me_reconnect_success_total 2766
telemt_me_reader_eof_total 2870
telemt_me_idle_close_by_peer_total 2870
telemt_me_route_drop_no_conn_total 27117
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 210
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 99
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2870
telemt_me_writer_restored_same_endpoint_total 2759
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 66306
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 1308350064 (1.22 GB)
telemt_user_octets_to_client{user="hello"} 27577317220 (25.68 GB)
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 21364.6 (5h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89745
telemt_connections_bad_total 997
telemt_handshake_timeouts_total 586
telemt_upstream_connect_attempt_total 15229
telemt_upstream_connect_success_total 15200
telemt_upstream_connect_attempts_per_request{bucket="1"} 15200
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 196
telemt_me_reconnect_attempts_total 2758
telemt_me_reconnect_success_total 2748
telemt_me_reader_eof_total 2847
telemt_me_idle_close_by_peer_total 2847
telemt_me_route_drop_no_conn_total 29734
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 99
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2849
telemt_me_writer_restored_same_endpoint_total 2741
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 86693
telemt_user_connections_current{user="hello"} 261
telemt_user_octets_from_client{user="hello"} 21899297968 (20.40 GB)
telemt_user_octets_to_client{user="hello"} 49989837012 (46.56 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 43
```