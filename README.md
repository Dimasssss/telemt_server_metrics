# Server Metrics 2026-03-04 22:39:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 6394.7 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70971
telemt_connections_bad_total 1346
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 5672
telemt_upstream_connect_success_total 5610
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5610
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2278
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 1602
telemt_me_reconnect_success_total 1612
telemt_me_reader_eof_total 1637
telemt_me_idle_close_by_peer_total 1637
telemt_me_route_drop_no_conn_total 17577
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_restored_same_endpoint_total 1592
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 59603
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 2317939764 (2.16 GB)
telemt_user_octets_to_client{user="hello"} 30155366104 (28.08 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 6389.4 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25034
telemt_connections_bad_total 679
telemt_handshake_timeouts_total 175
telemt_upstream_connect_attempt_total 6364
telemt_upstream_connect_success_total 6282
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 6282
telemt_upstream_connect_attempts_per_request{bucket="2"} 28
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2496
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2045
telemt_me_reconnect_success_total 2047
telemt_me_reader_eof_total 2075
telemt_me_idle_close_by_peer_total 2074
telemt_me_route_drop_no_conn_total 7842
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 115
telemt_desync_full_logged_total 50
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 2099
telemt_me_writer_restored_same_endpoint_total 2028
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 23450
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 217320724 (207.25 MB)
telemt_user_octets_to_client{user="hello"} 6747939116 (6.28 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 6386.1 (1h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57253
telemt_connections_bad_total 996
telemt_handshake_timeouts_total 240
telemt_upstream_connect_attempt_total 2319
telemt_upstream_connect_success_total 2296
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 2296
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 982
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 77
telemt_me_reconnect_success_total 90
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 75
telemt_me_route_drop_no_conn_total 17409
telemt_me_single_endpoint_shadow_rotate_total 28
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 75
telemt_me_writer_restored_same_endpoint_total 70
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 52476
telemt_user_connections_current{user="hello"} 307
telemt_user_octets_from_client{user="hello"} 806742440 (769.37 MB)
telemt_user_octets_to_client{user="hello"} 22791388800 (21.23 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 38434.3 (10h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519779
telemt_connections_bad_total 69832
telemt_handshake_timeouts_total 14666
telemt_upstream_connect_attempt_total 16693
telemt_upstream_connect_success_total 16693
telemt_upstream_connect_attempts_per_request{bucket="1"} 16693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 221
telemt_me_reconnect_attempts_total 2183
telemt_me_reconnect_success_total 2168
telemt_me_reader_eof_total 2210
telemt_me_idle_close_by_peer_total 2210
telemt_me_route_drop_no_conn_total 178525
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 14
telemt_pool_force_close_total 440
telemt_me_writer_removed_unexpected_total 2211
telemt_me_writer_restored_same_endpoint_total 2142
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 407038
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 5707486116 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 154570530604 (143.96 GB)
telemt_user_unique_ips_current{user="hello"} 38
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 38793.6 (10h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 519437
telemt_connections_bad_total 3772
telemt_handshake_timeouts_total 5755
telemt_upstream_connect_attempt_total 23077
telemt_upstream_connect_success_total 22953
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 22953
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 322
telemt_me_reconnect_attempts_total 4759
telemt_me_reconnect_success_total 4745
telemt_me_reader_eof_total 4917
telemt_me_idle_close_by_peer_total 4917
telemt_me_route_drop_no_conn_total 229025
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 827
telemt_desync_full_logged_total 300
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4919
telemt_me_writer_restored_same_endpoint_total 4724
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 469347
telemt_user_connections_current{user="hello"} 216
telemt_user_octets_from_client{user="hello"} 7228578980 (6.73 GB)
telemt_user_octets_to_client{user="hello"} 153093198660 (142.58 GB)
telemt_user_unique_ips_current{user="hello"} 32
```