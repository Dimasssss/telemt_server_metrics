# Server Metrics 2026-03-03 22:03:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 3149.8 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31304
telemt_connections_bad_total 265
telemt_handshake_timeouts_total 66
telemt_upstream_connect_attempt_total 1418
telemt_upstream_connect_success_total 1409
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 1409
telemt_upstream_connect_attempts_per_request{bucket="2"} 2
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 113
telemt_me_reconnect_success_total 127
telemt_me_reader_eof_total 108
telemt_me_idle_close_by_peer_total 108
telemt_me_route_drop_no_conn_total 12271
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 59
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_me_writer_removed_unexpected_total 108
telemt_me_writer_restored_same_endpoint_total 107
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 30175
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 283168040 (270.05 MB)
telemt_user_octets_to_client{user="hello"} 13376046852 (12.46 GB)
telemt_user_unique_ips_current{user="hello"} 58
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 3146.5 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12796
telemt_connections_bad_total 9
telemt_handshake_timeouts_total 2075
telemt_upstream_connect_attempt_total 1858
telemt_upstream_connect_success_total 1755
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 1755
telemt_upstream_connect_attempts_per_request{bucket="2"} 49
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 324
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 324
telemt_me_idle_close_by_peer_total 323
telemt_me_route_drop_no_conn_total 4932
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 38
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 23
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_me_writer_removed_unexpected_total 324
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 10521
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 58936304 (56.21 MB)
telemt_user_octets_to_client{user="hello"} 2786733088 (2.60 GB)
telemt_user_unique_ips_current{user="hello"} 14
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 3145.2 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31910
telemt_connections_bad_total 8646
telemt_handshake_timeouts_total 60
telemt_upstream_connect_attempt_total 1745
telemt_upstream_connect_success_total 1728
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1728
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 762
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 182
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 6564
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 84
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 183
telemt_me_writer_restored_same_endpoint_total 177
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 22291
telemt_user_connections_current{user="hello"} 201
telemt_user_octets_from_client{user="hello"} 171474324 (163.53 MB)
telemt_user_octets_to_client{user="hello"} 9814254804 (9.14 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 3144.3 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14140
telemt_connections_bad_total 28
telemt_handshake_timeouts_total 223
telemt_upstream_connect_attempt_total 1694
telemt_upstream_connect_success_total 1681
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 1681
telemt_upstream_connect_attempts_per_request{bucket="2"} 6
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 139
telemt_me_reconnect_success_total 156
telemt_me_reader_eof_total 138
telemt_me_idle_close_by_peer_total 138
telemt_me_route_drop_no_conn_total 6198
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 138
telemt_me_writer_restored_same_endpoint_total 137
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 13650
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 136485476 (130.16 MB)
telemt_user_octets_to_client{user="hello"} 6038712760 (5.62 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 3142.9 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30761
telemt_connections_bad_total 2
telemt_handshake_timeouts_total 7309
telemt_upstream_connect_attempt_total 1560
telemt_upstream_connect_success_total 1529
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 1529
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 255
telemt_me_reconnect_success_total 271
telemt_me_reader_eof_total 256
telemt_me_idle_close_by_peer_total 256
telemt_me_route_drop_no_conn_total 23966
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 3
telemt_desync_full_logged_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_me_writer_removed_unexpected_total 256
telemt_me_writer_restored_same_endpoint_total 250
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 22962
telemt_user_connections_current{user="hello"} 259
telemt_user_octets_from_client{user="hello"} 143948804 (137.28 MB)
telemt_user_octets_to_client{user="hello"} 5947044064 (5.54 GB)
telemt_user_unique_ips_current{user="hello"} 31
```