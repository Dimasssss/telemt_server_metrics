# Server Metrics 2026-03-06 09:30:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 3507.2 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 97274
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 362
telemt_upstream_connect_attempt_total 964
telemt_upstream_connect_success_total 960
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 11
telemt_me_reconnect_success_total 8
telemt_me_reader_eof_total 12
telemt_me_idle_close_by_peer_total 12
telemt_me_route_drop_no_conn_total 29878
telemt_me_route_drop_channel_closed_total 1
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 456
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 104
telemt_desync_frames_bucket_total{bucket="3_10"} 161
telemt_desync_frames_bucket_total{bucket="gt_10"} 191
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 12
telemt_me_writer_restored_same_endpoint_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 78510
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 1129001640 (1.05 GB)
telemt_user_octets_to_client{user="hello"} 26312281324 (24.51 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 3504.7 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62224
telemt_connections_bad_total 321
telemt_handshake_timeouts_total 29549
telemt_upstream_connect_attempt_total 1512
telemt_upstream_connect_success_total 1512
telemt_upstream_connect_attempts_per_request{bucket="1"} 1512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 711
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 45
telemt_me_reconnect_success_total 42
telemt_me_reader_eof_total 44
telemt_me_idle_close_by_peer_total 44
telemt_me_route_drop_no_conn_total 12546
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 118
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_removed_unexpected_total 44
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 31689
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 485171764 (462.70 MB)
telemt_user_octets_to_client{user="hello"} 10193124664 (9.49 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 3488.0 (0h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72983
telemt_connections_bad_total 279
telemt_handshake_timeouts_total 9926
telemt_upstream_connect_attempt_total 1582
telemt_upstream_connect_success_total 1567
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1579
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 640
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 49
telemt_me_reconnect_attempts_total 84
telemt_me_reconnect_success_total 75
telemt_me_reader_eof_total 75
telemt_me_idle_close_by_peer_total 74
telemt_me_route_drop_no_conn_total 22567
telemt_me_single_endpoint_shadow_rotate_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 169
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_me_writer_removed_unexpected_total 80
telemt_me_writer_restored_same_endpoint_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 59825
telemt_user_connections_current{user="hello"} 596
telemt_user_octets_from_client{user="hello"} 1201980708 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 15821493140 (14.73 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 3472.5 (0h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57665
telemt_connections_bad_total 3134
telemt_handshake_timeouts_total 11693
telemt_upstream_connect_attempt_total 1616
telemt_upstream_connect_success_total 1600
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 884
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 716
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 132
telemt_me_reconnect_success_total 127
telemt_me_reader_eof_total 129
telemt_me_idle_close_by_peer_total 129
telemt_me_route_drop_no_conn_total 20591
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 69
telemt_me_writer_removed_unexpected_total 129
telemt_me_writer_restored_same_endpoint_total 125
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 41201
telemt_user_connections_current{user="hello"} 441
telemt_user_octets_from_client{user="hello"} 747577228 (712.95 MB)
telemt_user_octets_to_client{user="hello"} 11977405192 (11.15 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 3414.2 (0h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 50522
telemt_connections_bad_total 261
telemt_handshake_timeouts_total 221
telemt_upstream_connect_attempt_total 1656
telemt_upstream_connect_success_total 1631
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1026
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 226
telemt_me_reconnect_success_total 223
telemt_me_reader_eof_total 220
telemt_me_idle_close_by_peer_total 220
telemt_me_route_drop_no_conn_total 21448
telemt_me_single_endpoint_shadow_rotate_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 88
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_me_writer_removed_unexpected_total 223
telemt_me_writer_restored_same_endpoint_total 218
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 46142
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 831783732 (793.25 MB)
telemt_user_octets_to_client{user="hello"} 20158104568 (18.77 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 82
```