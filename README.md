# Server Metrics 2026-03-06 20:12:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 7480.9 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171965
telemt_connections_bad_total 1779
telemt_handshake_timeouts_total 7080
telemt_upstream_connect_attempt_total 10924
telemt_upstream_connect_success_total 10817
telemt_upstream_connect_fail_total 42
telemt_upstream_connect_attempts_per_request{bucket="1"} 10859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3676
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 42
telemt_me_keepalive_timeout_total 325
telemt_me_reconnect_attempts_total 3348
telemt_me_reconnect_success_total 3332
telemt_me_reader_eof_total 4354
telemt_me_idle_close_by_peer_total 4354
telemt_me_route_drop_no_conn_total 67423
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 610
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 433
telemt_desync_frames_bucket_total{bucket="1_2"} 181
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 196
telemt_pool_swap_total 2
telemt_pool_force_close_total 184
telemt_pool_stale_pick_total 151
telemt_me_writer_removed_unexpected_total 4378
telemt_me_writer_restored_same_endpoint_total 3326
telemt_me_writer_removed_unexpected_minus_restored_total 1052
telemt_user_connections_total{user="hello"} 150643
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 2355155192 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 53834755124 (50.14 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 7480.5 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61800
telemt_connections_bad_total 51
telemt_handshake_timeouts_total 2466
telemt_upstream_connect_attempt_total 14938
telemt_upstream_connect_success_total 14937
telemt_upstream_connect_attempts_per_request{bucket="1"} 14937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11192
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 245
telemt_me_reconnect_attempts_total 5514
telemt_me_reconnect_success_total 5508
telemt_me_reader_eof_total 7680
telemt_me_idle_close_by_peer_total 7678
telemt_me_route_drop_no_conn_total 22407
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 262
telemt_desync_full_logged_total 86
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 114
telemt_desync_frames_bucket_total{bucket="gt_10"} 115
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 7680
telemt_me_writer_restored_same_endpoint_total 5506
telemt_me_writer_removed_unexpected_minus_restored_total 2174
telemt_user_connections_total{user="hello"} 55004
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 1050475832 (1001.81 MB)
telemt_user_octets_to_client{user="hello"} 18013413604 (16.78 GB)
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 7480.6 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 121518
telemt_connections_bad_total 280
telemt_handshake_timeouts_total 1274
telemt_upstream_connect_attempt_total 9470
telemt_upstream_connect_success_total 9411
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 539
telemt_me_reconnect_attempts_total 2027
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 2694
telemt_me_idle_close_by_peer_total 2692
telemt_me_route_drop_no_conn_total 49632
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 573
telemt_desync_full_logged_total 134
telemt_desync_suppressed_total 439
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 235
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 4
telemt_pool_force_close_total 133
telemt_pool_stale_pick_total 116
telemt_me_writer_removed_unexpected_total 2750
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_writer_removed_unexpected_minus_restored_total 740
telemt_user_connections_total{user="hello"} 111215
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 5440891496 (5.07 GB)
telemt_user_octets_to_client{user="hello"} 30659137892 (28.55 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 7480.9 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133285
telemt_connections_bad_total 46588
telemt_handshake_timeouts_total 8904
telemt_upstream_connect_attempt_total 11042
telemt_upstream_connect_success_total 11009
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 11024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 210
telemt_me_reconnect_attempts_total 3434
telemt_me_reconnect_success_total 3424
telemt_me_reader_eof_total 4391
telemt_me_idle_close_by_peer_total 4391
telemt_me_route_drop_no_conn_total 27358
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 58
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 16
telemt_pool_swap_total 4
telemt_pool_force_close_total 155
telemt_pool_stale_pick_total 450
telemt_me_writer_removed_unexpected_total 4393
telemt_me_writer_restored_same_endpoint_total 3420
telemt_me_writer_removed_unexpected_minus_restored_total 973
telemt_user_connections_total{user="hello"} 75316
telemt_user_connections_current{user="hello"} 290
telemt_user_octets_from_client{user="hello"} 1050162624 (1001.51 MB)
telemt_user_octets_to_client{user="hello"} 25191222520 (23.46 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 7479.3 (2h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103503
telemt_connections_bad_total 448
telemt_handshake_timeouts_total 599
telemt_upstream_connect_attempt_total 10574
telemt_upstream_connect_success_total 10520
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 10532
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 442
telemt_me_reconnect_attempts_total 2961
telemt_me_reconnect_success_total 2948
telemt_me_reader_eof_total 3976
telemt_me_idle_close_by_peer_total 3975
telemt_me_route_drop_no_conn_total 37672
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 520
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 154
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 3
telemt_pool_force_close_total 147
telemt_pool_stale_pick_total 78
telemt_me_writer_removed_unexpected_total 4012
telemt_me_writer_restored_same_endpoint_total 2946
telemt_me_writer_removed_unexpected_minus_restored_total 1066
telemt_user_connections_total{user="hello"} 98032
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 8606202272 (8.02 GB)
telemt_user_octets_to_client{user="hello"} 35200877704 (32.78 GB)
telemt_user_unique_ips_current{user="hello"} 112
telemt_user_unique_ips_recent_window{user="hello"} 50
```