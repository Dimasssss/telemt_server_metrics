# Server Metrics 2026-03-06 19:26:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 4709.6 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 117988
telemt_connections_bad_total 1380
telemt_handshake_timeouts_total 3812
telemt_upstream_connect_attempt_total 5813
telemt_upstream_connect_success_total 5741
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 5769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3737
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 227
telemt_me_reconnect_attempts_total 1608
telemt_me_reconnect_success_total 1598
telemt_me_reader_eof_total 2014
telemt_me_idle_close_by_peer_total 2014
telemt_me_route_drop_no_conn_total 48508
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 494
telemt_desync_full_logged_total 139
telemt_desync_suppressed_total 355
telemt_desync_frames_bucket_total{bucket="1_2"} 153
telemt_desync_frames_bucket_total{bucket="3_10"} 181
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 146
telemt_me_writer_removed_unexpected_total 2034
telemt_me_writer_restored_same_endpoint_total 1592
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 104230
telemt_user_connections_current{user="hello"} 714
telemt_user_octets_from_client{user="hello"} 1804174912 (1.68 GB)
telemt_user_octets_to_client{user="hello"} 34326608612 (31.97 GB)
telemt_user_unique_ips_current{user="hello"} 214
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 4709.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41900
telemt_connections_bad_total 23
telemt_handshake_timeouts_total 2309
telemt_upstream_connect_attempt_total 8343
telemt_upstream_connect_success_total 8342
telemt_upstream_connect_attempts_per_request{bucket="1"} 8342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6573
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 2916
telemt_me_reconnect_success_total 2912
telemt_me_reader_eof_total 3852
telemt_me_idle_close_by_peer_total 3852
telemt_me_route_drop_no_conn_total 15870
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 155
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 108
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 3852
telemt_me_writer_restored_same_endpoint_total 2910
telemt_me_writer_removed_unexpected_minus_restored_total 942
telemt_user_connections_total{user="hello"} 38054
telemt_user_connections_current{user="hello"} 359
telemt_user_octets_from_client{user="hello"} 861576808 (821.66 MB)
telemt_user_octets_to_client{user="hello"} 11144311172 (10.38 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 4709.4 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76657
telemt_connections_bad_total 244
telemt_handshake_timeouts_total 929
telemt_upstream_connect_attempt_total 5011
telemt_upstream_connect_success_total 4993
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 888
telemt_me_reconnect_success_total 887
telemt_me_reader_eof_total 1153
telemt_me_idle_close_by_peer_total 1153
telemt_me_route_drop_no_conn_total 24404
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 400
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 172
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 3
telemt_pool_force_close_total 88
telemt_pool_stale_pick_total 109
telemt_me_writer_removed_unexpected_total 1155
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 71355
telemt_user_connections_current{user="hello"} 470
telemt_user_octets_from_client{user="hello"} 3048675156 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 19402294372 (18.07 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 4709.7 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96115
telemt_connections_bad_total 38652
telemt_handshake_timeouts_total 4457
telemt_upstream_connect_attempt_total 6413
telemt_upstream_connect_success_total 6394
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 6409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 1817
telemt_me_reconnect_success_total 1811
telemt_me_reader_eof_total 2357
telemt_me_idle_close_by_peer_total 2357
telemt_me_route_drop_no_conn_total 16805
telemt_me_single_endpoint_shadow_rotate_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 55
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 2
telemt_pool_force_close_total 70
telemt_pool_stale_pick_total 308
telemt_me_writer_removed_unexpected_total 2357
telemt_me_writer_restored_same_endpoint_total 1807
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 51142
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 428694016 (408.83 MB)
telemt_user_octets_to_client{user="hello"} 17025912260 (15.86 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 4708.6 (1h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69905
telemt_connections_bad_total 438
telemt_handshake_timeouts_total 410
telemt_upstream_connect_attempt_total 6858
telemt_upstream_connect_success_total 6839
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 6847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2218
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 2112
telemt_me_reconnect_success_total 2107
telemt_me_reader_eof_total 2998
telemt_me_idle_close_by_peer_total 2997
telemt_me_route_drop_no_conn_total 25813
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 405
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 318
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 2
telemt_pool_force_close_total 81
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 3002
telemt_me_writer_restored_same_endpoint_total 2105
telemt_me_writer_removed_unexpected_minus_restored_total 897
telemt_user_connections_total{user="hello"} 65987
telemt_user_connections_current{user="hello"} 421
telemt_user_octets_from_client{user="hello"} 8266866548 (7.70 GB)
telemt_user_octets_to_client{user="hello"} 26024222300 (24.24 GB)
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 71
```