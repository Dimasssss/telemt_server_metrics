# Server Metrics 2026-03-06 03:47:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 19533.1 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135214
telemt_connections_bad_total 15926
telemt_handshake_timeouts_total 2813
telemt_upstream_connect_attempt_total 21828
telemt_upstream_connect_success_total 21651
telemt_upstream_connect_fail_total 83
telemt_upstream_connect_attempts_per_request{bucket="1"} 21651
telemt_upstream_connect_attempts_per_request{bucket="2"} 83
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8453
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 83
telemt_me_keepalive_timeout_total 229
telemt_me_reconnect_attempts_total 8150
telemt_me_reconnect_success_total 8124
telemt_me_reader_eof_total 8407
telemt_me_idle_close_by_peer_total 8407
telemt_me_route_drop_no_conn_total 37038
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 2
telemt_pool_force_close_total 93
telemt_me_writer_removed_unexpected_total 8407
telemt_me_writer_restored_same_endpoint_total 8118
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 109072
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 1408939116 (1.31 GB)
telemt_user_octets_to_client{user="hello"} 42164674400 (39.27 GB)
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 19528.5 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45842
telemt_connections_bad_total 112
telemt_handshake_timeouts_total 616
telemt_upstream_connect_attempt_total 15807
telemt_upstream_connect_success_total 15805
telemt_upstream_connect_attempts_per_request{bucket="1"} 15805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6914
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 199
telemt_me_reconnect_attempts_total 2954
telemt_me_reconnect_success_total 2940
telemt_me_reader_eof_total 2979
telemt_me_idle_close_by_peer_total 2979
telemt_me_route_drop_no_conn_total 13653
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 54
telemt_desync_suppressed_total 99
telemt_desync_frames_bucket_total{bucket="1_2"} 45
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 2980
telemt_me_writer_restored_same_endpoint_total 2934
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 44296
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 314337264 (299.78 MB)
telemt_user_octets_to_client{user="hello"} 10814578484 (10.07 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 19525.9 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80511
telemt_connections_bad_total 785
telemt_handshake_timeouts_total 1616
telemt_upstream_connect_attempt_total 18957
telemt_upstream_connect_success_total 18809
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 18809
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7704
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 232
telemt_me_reconnect_attempts_total 5845
telemt_me_reconnect_success_total 5824
telemt_me_reader_eof_total 6093
telemt_me_idle_close_by_peer_total 6093
telemt_me_route_drop_no_conn_total 22260
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 32
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 6097
telemt_me_writer_restored_same_endpoint_total 5816
telemt_me_writer_removed_unexpected_minus_restored_total 281
telemt_user_connections_total{user="hello"} 75305
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 752755828 (717.88 MB)
telemt_user_octets_to_client{user="hello"} 25338937376 (23.60 GB)
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 19522.4 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66656
telemt_connections_bad_total 958
telemt_handshake_timeouts_total 4130
telemt_upstream_connect_attempt_total 13029
telemt_upstream_connect_success_total 12988
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 12988
telemt_upstream_connect_attempts_per_request{bucket="2"} 20
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 143
telemt_me_reconnect_attempts_total 2618
telemt_me_reconnect_success_total 2599
telemt_me_reader_eof_total 2701
telemt_me_idle_close_by_peer_total 2701
telemt_me_route_drop_no_conn_total 24053
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 102
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 7
telemt_pool_force_close_total 148
telemt_me_writer_removed_unexpected_total 2701
telemt_me_writer_restored_same_endpoint_total 2592
telemt_me_writer_removed_unexpected_minus_restored_total 109
telemt_user_connections_total{user="hello"} 58040
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 608101860 (579.93 MB)
telemt_user_octets_to_client{user="hello"} 25578591568 (23.82 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 19521.5 (5h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79091
telemt_connections_bad_total 871
telemt_handshake_timeouts_total 533
telemt_upstream_connect_attempt_total 13037
telemt_upstream_connect_success_total 13011
telemt_upstream_connect_attempts_per_request{bucket="1"} 13011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5064
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 167
telemt_me_reconnect_attempts_total 1890
telemt_me_reconnect_success_total 1883
telemt_me_reader_eof_total 1937
telemt_me_idle_close_by_peer_total 1937
telemt_me_route_drop_no_conn_total 25607
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 78
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1939
telemt_me_writer_restored_same_endpoint_total 1877
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 76535
telemt_user_connections_current{user="hello"} 254
telemt_user_octets_from_client{user="hello"} 13487253776 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 46236353472 (43.06 GB)
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 42
```