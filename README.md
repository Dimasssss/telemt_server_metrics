# Server Metrics 2026-03-06 04:12:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 21069.1 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148871
telemt_connections_bad_total 15928
telemt_handshake_timeouts_total 2866
telemt_upstream_connect_attempt_total 23055
telemt_upstream_connect_success_total 22878
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 22878
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 250
telemt_me_reconnect_attempts_total 8679
telemt_me_reconnect_success_total 8650
telemt_me_reader_eof_total 8963
telemt_me_idle_close_by_peer_total 8963
telemt_me_route_drop_no_conn_total 41534
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 366
telemt_desync_full_logged_total 130
telemt_desync_suppressed_total 236
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 3
telemt_pool_force_close_total 153
telemt_me_writer_removed_unexpected_total 8963
telemt_me_writer_restored_same_endpoint_total 8644
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 122311
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 2571493904 (2.39 GB)
telemt_user_octets_to_client{user="hello"} 46291413692 (43.11 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 69
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 21064.5 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 52131
telemt_connections_bad_total 115
telemt_handshake_timeouts_total 722
telemt_upstream_connect_attempt_total 18560
telemt_upstream_connect_success_total 18558
telemt_upstream_connect_attempts_per_request{bucket="1"} 18558
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10491
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 220
telemt_me_reconnect_attempts_total 4220
telemt_me_reconnect_success_total 4204
telemt_me_reader_eof_total 4283
telemt_me_idle_close_by_peer_total 4283
telemt_me_route_drop_no_conn_total 15547
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4284
telemt_me_writer_restored_same_endpoint_total 4198
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 50363
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 385465636 (367.61 MB)
telemt_user_octets_to_client{user="hello"} 12541980860 (11.68 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 21062.0 (5h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89763
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 1654
telemt_upstream_connect_attempt_total 19776
telemt_upstream_connect_success_total 19608
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 19608
telemt_upstream_connect_attempts_per_request{bucket="2"} 75
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11626
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 5981
telemt_me_reconnect_success_total 5960
telemt_me_reader_eof_total 6231
telemt_me_idle_close_by_peer_total 6231
telemt_me_route_drop_no_conn_total 25367
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 178
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 124
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 49
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6235
telemt_me_writer_restored_same_endpoint_total 5952
telemt_me_writer_removed_unexpected_minus_restored_total 283
telemt_user_connections_total{user="hello"} 84183
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 872776892 (832.34 MB)
telemt_user_octets_to_client{user="hello"} 28770082712 (26.79 GB)
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 21058.7 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75770
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 4449
telemt_upstream_connect_attempt_total 14173
telemt_upstream_connect_success_total 14126
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 14126
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8287
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2781
telemt_me_reconnect_success_total 2761
telemt_me_reader_eof_total 2865
telemt_me_idle_close_by_peer_total 2865
telemt_me_route_drop_no_conn_total 26789
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 205
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 130
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 97
telemt_pool_swap_total 8
telemt_pool_force_close_total 168
telemt_me_writer_removed_unexpected_total 2865
telemt_me_writer_restored_same_endpoint_total 2754
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 65070
telemt_user_connections_current{user="hello"} 231
telemt_user_octets_from_client{user="hello"} 882711636 (841.82 MB)
telemt_user_octets_to_client{user="hello"} 27341717500 (25.46 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 21057.6 (5h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88033
telemt_connections_bad_total 990
telemt_handshake_timeouts_total 575
telemt_upstream_connect_attempt_total 15174
telemt_upstream_connect_success_total 15145
telemt_upstream_connect_attempts_per_request{bucket="1"} 15145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 194
telemt_me_reconnect_attempts_total 2758
telemt_me_reconnect_success_total 2748
telemt_me_reader_eof_total 2847
telemt_me_idle_close_by_peer_total 2847
telemt_me_route_drop_no_conn_total 29277
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 43
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 7
telemt_pool_force_close_total 125
telemt_me_writer_removed_unexpected_total 2849
telemt_me_writer_restored_same_endpoint_total 2741
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 85016
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 18697490716 (17.41 GB)
telemt_user_octets_to_client{user="hello"} 49143009656 (45.77 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 47
```