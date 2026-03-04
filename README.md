# Server Metrics 2026-03-04 22:19:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 5166.0 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59967
telemt_connections_bad_total 1343
telemt_handshake_timeouts_total 431
telemt_upstream_connect_attempt_total 3752
telemt_upstream_connect_success_total 3710
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 3710
telemt_upstream_connect_attempts_per_request{bucket="2"} 16
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 54
telemt_me_reconnect_attempts_total 818
telemt_me_reconnect_success_total 830
telemt_me_reader_eof_total 830
telemt_me_idle_close_by_peer_total 830
telemt_me_route_drop_no_conn_total 14637
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 120
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 50
telemt_desync_frames_bucket_total{bucket="1_2"} 49
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_restored_same_endpoint_total 810
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 50090
telemt_user_connections_current{user="hello"} 404
telemt_user_octets_from_client{user="hello"} 2229506700 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 23445347008 (21.84 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 5160.5 (1h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21932
telemt_connections_bad_total 675
telemt_handshake_timeouts_total 162
telemt_upstream_connect_attempt_total 4101
telemt_upstream_connect_success_total 4053
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 4053
telemt_upstream_connect_attempts_per_request{bucket="2"} 23
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2341
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 937
telemt_me_reconnect_success_total 947
telemt_me_reader_eof_total 949
telemt_me_idle_close_by_peer_total 949
telemt_me_route_drop_no_conn_total 6255
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 108
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 64
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_me_writer_removed_unexpected_total 949
telemt_me_writer_restored_same_endpoint_total 928
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 20410
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 182868568 (174.40 MB)
telemt_user_octets_to_client{user="hello"} 5391850928 (5.02 GB)
telemt_user_unique_ips_current{user="hello"} 25
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 5157.2 (1h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 49720
telemt_connections_bad_total 965
telemt_handshake_timeouts_total 229
telemt_upstream_connect_attempt_total 1575
telemt_upstream_connect_success_total 1555
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1555
telemt_upstream_connect_attempts_per_request{bucket="2"} 5
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 677
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 19
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 14787
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 136
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 94
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 2
telemt_pool_force_close_total 51
telemt_me_writer_removed_unexpected_total 16
telemt_me_writer_restored_same_endpoint_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 45057
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 658042228 (627.56 MB)
telemt_user_octets_to_client{user="hello"} 18093740024 (16.85 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 37205.5 (10h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 511665
telemt_connections_bad_total 67756
telemt_handshake_timeouts_total 14646
telemt_upstream_connect_attempt_total 16175
telemt_upstream_connect_success_total 16175
telemt_upstream_connect_attempts_per_request{bucket="1"} 16175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 218
telemt_me_reconnect_attempts_total 2146
telemt_me_reconnect_success_total 2132
telemt_me_reader_eof_total 2172
telemt_me_idle_close_by_peer_total 2172
telemt_me_route_drop_no_conn_total 176388
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 696
telemt_desync_full_logged_total 293
telemt_desync_suppressed_total 403
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 196
telemt_desync_frames_bucket_total{bucket="gt_10"} 282
telemt_pool_swap_total 13
telemt_pool_force_close_total 423
telemt_me_writer_removed_unexpected_total 2173
telemt_me_writer_restored_same_endpoint_total 2108
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 401103
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 5647103944 (5.26 GB)
telemt_user_octets_to_client{user="hello"} 153523630012 (142.98 GB)
telemt_user_unique_ips_current{user="hello"} 32
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 37565.0 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 513372
telemt_connections_bad_total 3759
telemt_handshake_timeouts_total 5716
telemt_upstream_connect_attempt_total 22057
telemt_upstream_connect_success_total 21937
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21937
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12533
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 312
telemt_me_reconnect_attempts_total 4566
telemt_me_reconnect_success_total 4553
telemt_me_reader_eof_total 4718
telemt_me_idle_close_by_peer_total 4718
telemt_me_route_drop_no_conn_total 226873
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 151
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 826
telemt_desync_full_logged_total 299
telemt_desync_suppressed_total 527
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 8
telemt_pool_force_close_total 370
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 4721
telemt_me_writer_restored_same_endpoint_total 4532
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 463502
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 7163674824 (6.67 GB)
telemt_user_octets_to_client{user="hello"} 149117335504 (138.88 GB)
telemt_user_unique_ips_current{user="hello"} 33
```