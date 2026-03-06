# Server Metrics 2026-03-06 09:09:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.3

telemt_uptime_seconds 2274.9 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 66109
telemt_connections_bad_total 231
telemt_handshake_timeouts_total 157
telemt_upstream_connect_attempt_total 664
telemt_upstream_connect_success_total 661
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 358
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 8
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 10
telemt_me_idle_close_by_peer_total 10
telemt_me_route_drop_no_conn_total 16418
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 335
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 253
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 111
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_me_writer_removed_unexpected_total 10
telemt_me_writer_restored_same_endpoint_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 51601
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 823478940 (785.33 MB)
telemt_user_octets_to_client{user="hello"} 16549073636 (15.41 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## server2

```
telemt 3.3.3

telemt_uptime_seconds 2272.3 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38121
telemt_connections_bad_total 316
telemt_handshake_timeouts_total 15272
telemt_upstream_connect_attempt_total 724
telemt_upstream_connect_success_total 724
telemt_upstream_connect_attempts_per_request{bucket="1"} 724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 361
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 17
telemt_me_reconnect_success_total 16
telemt_me_reader_eof_total 17
telemt_me_idle_close_by_peer_total 17
telemt_me_route_drop_no_conn_total 8035
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 99
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_me_writer_removed_unexpected_total 17
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 21186
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 337754332 (322.11 MB)
telemt_user_octets_to_client{user="hello"} 7955345116 (7.41 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.3

telemt_uptime_seconds 2255.6 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47360
telemt_connections_bad_total 263
telemt_handshake_timeouts_total 7921
telemt_upstream_connect_attempt_total 815
telemt_upstream_connect_success_total 807
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 815
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 37
telemt_me_reconnect_success_total 31
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 32
telemt_me_route_drop_no_conn_total 13623
telemt_me_single_endpoint_shadow_rotate_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 97
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 37617
telemt_user_connections_current{user="hello"} 612
telemt_user_octets_from_client{user="hello"} 697707260 (665.39 MB)
telemt_user_octets_to_client{user="hello"} 11783066664 (10.97 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## server4

```
telemt 3.3.3

telemt_uptime_seconds 2240.1 (0h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39889
telemt_connections_bad_total 2017
telemt_handshake_timeouts_total 10561
telemt_upstream_connect_attempt_total 829
telemt_upstream_connect_success_total 820
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 482
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 338
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 29
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 14205
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 95
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 31
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_me_writer_removed_unexpected_total 27
telemt_me_writer_restored_same_endpoint_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 26324
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 568617444 (542.28 MB)
telemt_user_octets_to_client{user="hello"} 8526142252 (7.94 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server5

```
telemt 3.3.3

telemt_uptime_seconds 2181.9 (0h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 34139
telemt_connections_bad_total 259
telemt_handshake_timeouts_total 111
telemt_upstream_connect_attempt_total 808
telemt_upstream_connect_success_total 792
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 57
telemt_me_reconnect_success_total 60
telemt_me_reader_eof_total 55
telemt_me_idle_close_by_peer_total 55
telemt_me_route_drop_no_conn_total 13463
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 51
telemt_desync_full_logged_total 17
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 19
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_me_writer_removed_unexpected_total 55
telemt_me_writer_restored_same_endpoint_total 55
telemt_user_connections_total{user="hello"} 30260
telemt_user_connections_current{user="hello"} 537
telemt_user_octets_from_client{user="hello"} 637807904 (608.26 MB)
telemt_user_octets_to_client{user="hello"} 12822284732 (11.94 GB)
telemt_user_unique_ips_current{user="hello"} 151
telemt_user_unique_ips_recent_window{user="hello"} 99
```