# Server Metrics 2026-03-04 05:33:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 30175.0 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227915
telemt_connections_bad_total 2362
telemt_handshake_timeouts_total 4547
telemt_upstream_connect_attempt_total 20831
telemt_upstream_connect_success_total 20738
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 20738
telemt_upstream_connect_attempts_per_request{bucket="2"} 41
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11777
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8932
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 4602
telemt_me_reconnect_success_total 4582
telemt_me_reader_eof_total 4687
telemt_me_idle_close_by_peer_total 4687
telemt_me_route_drop_no_conn_total 73722
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 122
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 602
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 378
telemt_desync_frames_bucket_total{bucket="1_2"} 168
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 224
telemt_pool_swap_total 7
telemt_pool_force_close_total 253
telemt_me_writer_removed_unexpected_total 4687
telemt_me_writer_restored_same_endpoint_total 4562
telemt_me_writer_removed_unexpected_minus_restored_total 125
telemt_user_connections_total{user="hello"} 215336
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 2258059028 (2.10 GB)
telemt_user_octets_to_client{user="hello"} 71510116440 (66.60 GB)
telemt_user_unique_ips_current{user="hello"} 103
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 30171.5 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106168
telemt_connections_bad_total 357
telemt_handshake_timeouts_total 21845
telemt_upstream_connect_attempt_total 67893
telemt_upstream_connect_success_total 67109
telemt_upstream_connect_fail_total 376
telemt_upstream_connect_attempts_per_request{bucket="1"} 67103
telemt_upstream_connect_attempts_per_request{bucket="2"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45527
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21562
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 376
telemt_me_keepalive_timeout_total 1003
telemt_me_reconnect_attempts_total 40906
telemt_me_reconnect_success_total 40878
telemt_me_reader_eof_total 41896
telemt_me_idle_close_by_peer_total 41895
telemt_me_route_drop_no_conn_total 33742
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 131
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 234
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 126
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 1
telemt_pool_force_close_total 75
telemt_me_writer_removed_unexpected_total 41957
telemt_me_writer_restored_same_endpoint_total 40857
telemt_me_writer_removed_unexpected_minus_restored_total 1100
telemt_user_connections_total{user="hello"} 78130
telemt_user_connections_current{user="hello"} 327
telemt_user_octets_from_client{user="hello"} 690688068 (658.69 MB)
telemt_user_octets_to_client{user="hello"} 33036033052 (30.77 GB)
telemt_user_unique_ips_current{user="hello"} 41
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 30170.3 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238304
telemt_connections_bad_total 86692
telemt_handshake_timeouts_total 5014
telemt_upstream_connect_attempt_total 39814
telemt_upstream_connect_success_total 39563
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 39563
telemt_upstream_connect_attempts_per_request{bucket="2"} 117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16280
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_timeout_total 519
telemt_me_reconnect_attempts_total 16045
telemt_me_reconnect_success_total 16002
telemt_me_reader_eof_total 16855
telemt_me_idle_close_by_peer_total 16852
telemt_me_route_drop_no_conn_total 49428
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 129
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 346
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 218
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 16863
telemt_me_writer_restored_same_endpoint_total 15981
telemt_me_writer_removed_unexpected_minus_restored_total 882
telemt_user_connections_total{user="hello"} 141406
telemt_user_connections_current{user="hello"} 373
telemt_user_octets_from_client{user="hello"} 1014238156 (967.25 MB)
telemt_user_octets_to_client{user="hello"} 37390940296 (34.82 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 30169.3 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120650
telemt_connections_bad_total 8588
telemt_handshake_timeouts_total 1845
telemt_upstream_connect_attempt_total 21930
telemt_upstream_connect_success_total 21841
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 21841
telemt_upstream_connect_attempts_per_request{bucket="2"} 44
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 223
telemt_me_reconnect_attempts_total 3981
telemt_me_reconnect_success_total 3979
telemt_me_reader_eof_total 4026
telemt_me_idle_close_by_peer_total 4026
telemt_me_route_drop_no_conn_total 37248
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 127
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 133
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 77
telemt_desync_frames_bucket_total{bucket="1_2"} 28
telemt_desync_frames_bucket_total{bucket="3_10"} 72
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 8
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 4026
telemt_me_writer_restored_same_endpoint_total 3958
telemt_me_writer_removed_unexpected_minus_restored_total 68
telemt_user_connections_total{user="hello"} 104470
telemt_user_connections_current{user="hello"} 260
telemt_user_octets_from_client{user="hello"} 917247476 (874.76 MB)
telemt_user_octets_to_client{user="hello"} 38120224084 (35.50 GB)
telemt_user_unique_ips_current{user="hello"} 33
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 30167.9 (8h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255260
telemt_connections_bad_total 5432
telemt_handshake_timeouts_total 115381
telemt_upstream_connect_attempt_total 44462
telemt_upstream_connect_success_total 44166
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 44166
telemt_upstream_connect_attempts_per_request{bucket="2"} 138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26176
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 106
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 612
telemt_me_reconnect_attempts_total 21378
telemt_me_reconnect_success_total 21367
telemt_me_reader_eof_total 22550
telemt_me_idle_close_by_peer_total 22549
telemt_me_route_drop_no_conn_total 57910
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 130
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 184
telemt_desync_full_logged_total 57
telemt_desync_suppressed_total 127
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 4
telemt_pool_force_close_total 114
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 22563
telemt_me_writer_restored_same_endpoint_total 21342
telemt_me_writer_removed_unexpected_minus_restored_total 1221
telemt_user_connections_total{user="hello"} 129914
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 1730895276 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 29840562068 (27.79 GB)
telemt_user_unique_ips_current{user="hello"} 38
```