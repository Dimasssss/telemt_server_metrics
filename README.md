# Server Metrics 2026-03-04 00:21:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 11441.1 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82321
telemt_connections_bad_total 680
telemt_handshake_timeouts_total 325
telemt_upstream_connect_attempt_total 9474
telemt_upstream_connect_success_total 9431
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 9431
telemt_upstream_connect_attempts_per_request{bucket="2"} 17
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 101
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 2700
telemt_me_reader_eof_total 2756
telemt_me_idle_close_by_peer_total 2756
telemt_me_route_drop_no_conn_total 32392
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 2
telemt_pool_force_close_total 78
telemt_me_writer_removed_unexpected_total 2756
telemt_me_writer_restored_same_endpoint_total 2680
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 79564
telemt_user_connections_current{user="hello"} 273
telemt_user_octets_from_client{user="hello"} 638756904 (609.17 MB)
telemt_user_octets_to_client{user="hello"} 24912244064 (23.20 GB)
telemt_user_unique_ips_current{user="hello"} 55
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 11437.7 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38241
telemt_connections_bad_total 103
telemt_handshake_timeouts_total 8440
telemt_upstream_connect_attempt_total 20204
telemt_upstream_connect_success_total 19901
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 19895
telemt_upstream_connect_attempts_per_request{bucket="2"} 142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7009
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 580
telemt_me_reconnect_attempts_total 10578
telemt_me_reconnect_success_total 10575
telemt_me_reader_eof_total 10791
telemt_me_idle_close_by_peer_total 10790
telemt_me_route_drop_no_conn_total 14639
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 76
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 35
telemt_me_writer_removed_unexpected_total 10853
telemt_me_writer_restored_same_endpoint_total 10555
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 29244
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 182156316 (173.72 MB)
telemt_user_octets_to_client{user="hello"} 14611527160 (13.61 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 11436.4 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89731
telemt_connections_bad_total 28368
telemt_handshake_timeouts_total 1820
telemt_upstream_connect_attempt_total 12847
telemt_upstream_connect_success_total 12773
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 12773
telemt_upstream_connect_attempts_per_request{bucket="2"} 34
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5417
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 152
telemt_me_reconnect_attempts_total 4536
telemt_me_reconnect_success_total 4537
telemt_me_reader_eof_total 4725
telemt_me_idle_close_by_peer_total 4724
telemt_me_route_drop_no_conn_total 17869
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 202
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 78
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 1
telemt_pool_force_close_total 36
telemt_me_writer_removed_unexpected_total 4726
telemt_me_writer_restored_same_endpoint_total 4516
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 58315
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 355923644 (339.44 MB)
telemt_user_octets_to_client{user="hello"} 15071205596 (14.04 GB)
telemt_user_unique_ips_current{user="hello"} 20
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 11435.4 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 40130
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 506
telemt_upstream_connect_attempt_total 7842
telemt_upstream_connect_success_total 7813
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 7813
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3044
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 1258
telemt_me_reconnect_success_total 1270
telemt_me_reader_eof_total 1269
telemt_me_idle_close_by_peer_total 1269
telemt_me_route_drop_no_conn_total 14675
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 8
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 7
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 3
telemt_pool_force_close_total 89
telemt_me_writer_removed_unexpected_total 1269
telemt_me_writer_restored_same_endpoint_total 1250
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 38857
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 375679708 (358.28 MB)
telemt_user_octets_to_client{user="hello"} 10890498724 (10.14 GB)
telemt_user_unique_ips_current{user="hello"} 28
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 11433.9 (3h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96858
telemt_connections_bad_total 40
telemt_handshake_timeouts_total 40280
telemt_upstream_connect_attempt_total 13220
telemt_upstream_connect_success_total 13110
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 13110
telemt_upstream_connect_attempts_per_request{bucket="2"} 52
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7528
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 171
telemt_me_reconnect_attempts_total 5612
telemt_me_reconnect_success_total 5621
telemt_me_reader_eof_total 5947
telemt_me_idle_close_by_peer_total 5947
telemt_me_route_drop_no_conn_total 35037
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 53
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 1
telemt_pool_force_close_total 30
telemt_me_writer_removed_unexpected_total 5951
telemt_me_writer_restored_same_endpoint_total 5597
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 54750
telemt_user_connections_current{user="hello"} 119
telemt_user_octets_from_client{user="hello"} 272560232 (259.93 MB)
telemt_user_octets_to_client{user="hello"} 14343650588 (13.36 GB)
telemt_user_unique_ips_current{user="hello"} 9
```