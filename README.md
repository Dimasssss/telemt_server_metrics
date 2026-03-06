# Server Metrics 2026-03-06 19:36:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 5324.7 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130932
telemt_connections_bad_total 1381
telemt_handshake_timeouts_total 4418
telemt_upstream_connect_attempt_total 7228
telemt_upstream_connect_success_total 7152
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 2170
telemt_me_reconnect_success_total 2155
telemt_me_reader_eof_total 2754
telemt_me_idle_close_by_peer_total 2754
telemt_me_route_drop_no_conn_total 52388
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 531
telemt_desync_full_logged_total 150
telemt_desync_suppressed_total 381
telemt_desync_frames_bucket_total{bucket="1_2"} 158
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 149
telemt_me_writer_removed_unexpected_total 2774
telemt_me_writer_restored_same_endpoint_total 2149
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 114108
telemt_user_connections_current{user="hello"} 848
telemt_user_octets_from_client{user="hello"} 1979520784 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 37882104420 (35.28 GB)
telemt_user_unique_ips_current{user="hello"} 235
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 5324.7 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48198
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 2324
telemt_upstream_connect_attempt_total 9115
telemt_upstream_connect_success_total 9113
telemt_upstream_connect_attempts_per_request{bucket="1"} 9113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2074
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7035
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 3085
telemt_me_reconnect_success_total 3080
telemt_me_reader_eof_total 4043
telemt_me_idle_close_by_peer_total 4043
telemt_me_route_drop_no_conn_total 16915
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 190
telemt_desync_full_logged_total 58
telemt_desync_suppressed_total 132
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 74
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 4043
telemt_me_writer_restored_same_endpoint_total 3078
telemt_me_writer_removed_unexpected_minus_restored_total 965
telemt_user_connections_total{user="hello"} 42194
telemt_user_connections_current{user="hello"} 334
telemt_user_octets_from_client{user="hello"} 899343840 (857.68 MB)
telemt_user_octets_to_client{user="hello"} 12495482452 (11.64 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 5324.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85039
telemt_connections_bad_total 251
telemt_handshake_timeouts_total 983
telemt_upstream_connect_attempt_total 5926
telemt_upstream_connect_success_total 5906
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 1010
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 1296
telemt_me_idle_close_by_peer_total 1296
telemt_me_route_drop_no_conn_total 26730
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 416
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 319
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 177
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 1298
telemt_me_writer_restored_same_endpoint_total 1001
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 79554
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 3559486964 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 23274031556 (21.68 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 5325.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104279
telemt_connections_bad_total 40620
telemt_handshake_timeouts_total 5535
telemt_upstream_connect_attempt_total 7751
telemt_upstream_connect_success_total 7732
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 7747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3875
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 2355
telemt_me_reconnect_success_total 2349
telemt_me_reader_eof_total 3001
telemt_me_idle_close_by_peer_total 3001
telemt_me_route_drop_no_conn_total 18559
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 71
telemt_pool_stale_pick_total 308
telemt_me_writer_removed_unexpected_total 3001
telemt_me_writer_restored_same_endpoint_total 2345
telemt_me_writer_removed_unexpected_minus_restored_total 656
telemt_user_connections_total{user="hello"} 56126
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 551366804 (525.82 MB)
telemt_user_octets_to_client{user="hello"} 18730437580 (17.44 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 5323.6 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 77954
telemt_connections_bad_total 441
telemt_handshake_timeouts_total 446
telemt_upstream_connect_attempt_total 7364
telemt_upstream_connect_success_total 7342
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 7350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 2151
telemt_me_reconnect_success_total 2146
telemt_me_reader_eof_total 3042
telemt_me_idle_close_by_peer_total 3041
telemt_me_route_drop_no_conn_total 27686
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 452
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 2
telemt_pool_force_close_total 106
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3046
telemt_me_writer_restored_same_endpoint_total 2144
telemt_me_writer_removed_unexpected_minus_restored_total 902
telemt_user_connections_total{user="hello"} 73738
telemt_user_connections_current{user="hello"} 389
telemt_user_octets_from_client{user="hello"} 8338171148 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 29273849436 (27.26 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 60
```