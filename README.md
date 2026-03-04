# Server Metrics 2026-03-04 02:29:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 19118.6 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122394
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 1008
telemt_upstream_connect_attempt_total 15458
telemt_upstream_connect_success_total 15389
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 15389
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8707
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6661
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 4052
telemt_me_reconnect_success_total 4046
telemt_me_reader_eof_total 4138
telemt_me_idle_close_by_peer_total 4138
telemt_me_route_drop_no_conn_total 43872
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 209
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4138
telemt_me_writer_restored_same_endpoint_total 4026
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 117270
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 939296008 (895.78 MB)
telemt_user_octets_to_client{user="hello"} 34780656084 (32.39 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 19115.2 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57630
telemt_connections_bad_total 275
telemt_handshake_timeouts_total 14899
telemt_upstream_connect_attempt_total 44670
telemt_upstream_connect_success_total 44183
telemt_upstream_connect_fail_total 227
telemt_upstream_connect_attempts_per_request{bucket="1"} 44177
telemt_upstream_connect_attempts_per_request{bucket="2"} 233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14064
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 227
telemt_me_keepalive_timeout_total 800
telemt_me_reconnect_attempts_total 27200
telemt_me_reconnect_success_total 27183
telemt_me_reader_eof_total 27886
telemt_me_idle_close_by_peer_total 27885
telemt_me_route_drop_no_conn_total 19274
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 89
telemt_desync_full_logged_total 37
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 36
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 27947
telemt_me_writer_restored_same_endpoint_total 27163
telemt_me_writer_removed_unexpected_minus_restored_total 784
telemt_user_connections_total{user="hello"} 41807
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 329796036 (314.52 MB)
telemt_user_octets_to_client{user="hello"} 23513583748 (21.90 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 19114.0 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135934
telemt_connections_bad_total 48437
telemt_handshake_timeouts_total 3188
telemt_upstream_connect_attempt_total 22207
telemt_upstream_connect_success_total 22056
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 22056
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9012
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 281
telemt_me_reconnect_attempts_total 7515
telemt_me_reconnect_success_total 7501
telemt_me_reader_eof_total 7813
telemt_me_idle_close_by_peer_total 7811
telemt_me_route_drop_no_conn_total 26229
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 273
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 7814
telemt_me_writer_restored_same_endpoint_total 7480
telemt_me_writer_removed_unexpected_minus_restored_total 334
telemt_user_connections_total{user="hello"} 80993
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 492410056 (469.60 MB)
telemt_user_octets_to_client{user="hello"} 20048371012 (18.67 GB)
telemt_user_unique_ips_current{user="hello"} 15
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 19112.7 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 60698
telemt_connections_bad_total 188
telemt_handshake_timeouts_total 617
telemt_upstream_connect_attempt_total 11818
telemt_upstream_connect_success_total 11757
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 11757
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 119
telemt_me_reconnect_attempts_total 1580
telemt_me_reconnect_success_total 1586
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1591
telemt_me_route_drop_no_conn_total 20919
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 81
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1591
telemt_me_writer_restored_same_endpoint_total 1566
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 58808
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 486706572 (464.16 MB)
telemt_user_octets_to_client{user="hello"} 18792795760 (17.50 GB)
telemt_user_unique_ips_current{user="hello"} 23
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 19111.6 (5h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146585
telemt_connections_bad_total 81
telemt_handshake_timeouts_total 65701
telemt_upstream_connect_attempt_total 27945
telemt_upstream_connect_success_total 27769
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 27769
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 372
telemt_me_reconnect_attempts_total 14163
telemt_me_reconnect_success_total 14162
telemt_me_reader_eof_total 15049
telemt_me_idle_close_by_peer_total 15048
telemt_me_route_drop_no_conn_total 41461
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2059
telemt_me_writer_removed_unexpected_total 15054
telemt_me_writer_restored_same_endpoint_total 14138
telemt_me_writer_removed_unexpected_minus_restored_total 916
telemt_user_connections_total{user="hello"} 77990
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 393449684 (375.22 MB)
telemt_user_octets_to_client{user="hello"} 17389074036 (16.19 GB)
telemt_user_unique_ips_current{user="hello"} 15
```