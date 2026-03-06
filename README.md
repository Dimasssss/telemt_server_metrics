# Server Metrics 2026-03-06 10:01:08 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 5352.1 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150267
telemt_connections_bad_total 399
telemt_handshake_timeouts_total 1227
telemt_upstream_connect_attempt_total 1736
telemt_upstream_connect_success_total 1728
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1729
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 767
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 46
telemt_me_reconnect_success_total 42
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 65307
telemt_me_route_drop_channel_closed_total 2
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 787
telemt_desync_full_logged_total 207
telemt_desync_suppressed_total 580
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 292
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 1
telemt_pool_force_close_total 40
telemt_me_writer_removed_unexpected_total 47
telemt_me_writer_restored_same_endpoint_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 120999
telemt_user_connections_current{user="hello"} 1163
telemt_user_octets_from_client{user="hello"} 1821632868 (1.70 GB)
telemt_user_octets_to_client{user="hello"} 51797930104 (48.24 GB)
telemt_user_unique_ips_current{user="hello"} 311
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 5349.4 (1h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79074
telemt_connections_bad_total 347
telemt_handshake_timeouts_total 29816
telemt_upstream_connect_attempt_total 3175
telemt_upstream_connect_success_total 3175
telemt_upstream_connect_attempts_per_request{bucket="1"} 3175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1464
telemt_me_keepalive_timeout_total 33
telemt_me_reconnect_attempts_total 304
telemt_me_reconnect_success_total 299
telemt_me_reader_eof_total 307
telemt_me_idle_close_by_peer_total 307
telemt_me_route_drop_no_conn_total 19053
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 216
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 157
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_me_writer_removed_unexpected_total 307
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 47918
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 774458108 (738.58 MB)
telemt_user_octets_to_client{user="hello"} 15034492156 (14.00 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 5332.7 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 108697
telemt_connections_bad_total 470
telemt_handshake_timeouts_total 11815
telemt_upstream_connect_attempt_total 3154
telemt_upstream_connect_success_total 3135
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 3150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1172
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 65
telemt_me_reconnect_attempts_total 417
telemt_me_reconnect_success_total 406
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 411
telemt_me_route_drop_no_conn_total 34708
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 232
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 81
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 418
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 92937
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 1493092720 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 24768865620 (23.07 GB)
telemt_user_unique_ips_current{user="hello"} 207
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 5317.2 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82667
telemt_connections_bad_total 4824
telemt_handshake_timeouts_total 12921
telemt_upstream_connect_attempt_total 2966
telemt_upstream_connect_success_total 2946
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 2964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1277
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 512
telemt_me_reconnect_success_total 506
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 29502
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 175
telemt_desync_full_logged_total 60
telemt_desync_suppressed_total 115
telemt_desync_frames_bucket_total{bucket="1_2"} 38
telemt_desync_frames_bucket_total{bucket="3_10"} 55
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 1
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 512
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 62214
telemt_user_connections_current{user="hello"} 462
telemt_user_octets_from_client{user="hello"} 926398068 (883.48 MB)
telemt_user_octets_to_client{user="hello"} 18250681864 (17.00 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 5258.9 (1h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74567
telemt_connections_bad_total 270
telemt_handshake_timeouts_total 405
telemt_upstream_connect_attempt_total 3372
telemt_upstream_connect_success_total 3340
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 767
telemt_me_reconnect_success_total 762
telemt_me_reader_eof_total 783
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 36769
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 126
telemt_desync_full_logged_total 42
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 29
telemt_desync_frames_bucket_total{bucket="3_10"} 48
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_restored_same_endpoint_total 757
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 69498
telemt_user_connections_current{user="hello"} 580
telemt_user_octets_from_client{user="hello"} 1153810004 (1.07 GB)
telemt_user_octets_to_client{user="hello"} 32616464124 (30.38 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 109
```