# Server Metrics 2026-03-04 02:24:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 18811.5 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120989
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 1007
telemt_upstream_connect_attempt_total 15266
telemt_upstream_connect_success_total 15205
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 15205
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6583
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 158
telemt_me_reconnect_attempts_total 4044
telemt_me_reconnect_success_total 4038
telemt_me_reader_eof_total 4130
telemt_me_idle_close_by_peer_total 4130
telemt_me_route_drop_no_conn_total 43512
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 208
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 140
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4130
telemt_me_writer_restored_same_endpoint_total 4018
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 115900
telemt_user_connections_current{user="hello"} 309
telemt_user_octets_from_client{user="hello"} 930978112 (887.85 MB)
telemt_user_octets_to_client{user="hello"} 34461626816 (32.09 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 18808.1 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56962
telemt_connections_bad_total 274
telemt_handshake_timeouts_total 14702
telemt_upstream_connect_attempt_total 43540
telemt_upstream_connect_success_total 43062
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 43056
telemt_upstream_connect_attempts_per_request{bucket="2"} 229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13717
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 791
telemt_me_reconnect_attempts_total 26409
telemt_me_reconnect_success_total 26392
telemt_me_reader_eof_total 27080
telemt_me_idle_close_by_peer_total 27079
telemt_me_route_drop_no_conn_total 19106
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 80
telemt_desync_full_logged_total 35
telemt_desync_suppressed_total 45
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_me_writer_removed_unexpected_total 27141
telemt_me_writer_restored_same_endpoint_total 26372
telemt_me_writer_removed_unexpected_minus_restored_total 769
telemt_user_connections_total{user="hello"} 41320
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 326793772 (311.65 MB)
telemt_user_octets_to_client{user="hello"} 23157844876 (21.57 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 18806.9 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 134117
telemt_connections_bad_total 47647
telemt_handshake_timeouts_total 3187
telemt_upstream_connect_attempt_total 21690
telemt_upstream_connect_success_total 21549
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 21549
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8813
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 274
telemt_me_reconnect_attempts_total 7302
telemt_me_reconnect_success_total 7289
telemt_me_reader_eof_total 7588
telemt_me_idle_close_by_peer_total 7586
telemt_me_route_drop_no_conn_total 25580
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 269
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 176
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 99
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 7589
telemt_me_writer_restored_same_endpoint_total 7268
telemt_me_writer_removed_unexpected_minus_restored_total 321
telemt_user_connections_total{user="hello"} 79974
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 488328252 (465.71 MB)
telemt_user_octets_to_client{user="hello"} 19811652688 (18.45 GB)
telemt_user_unique_ips_current{user="hello"} 22
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 18805.9 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59833
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 610
telemt_upstream_connect_attempt_total 11597
telemt_upstream_connect_success_total 11544
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11544
telemt_upstream_connect_attempts_per_request{bucket="2"} 26
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7205
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4338
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1567
telemt_me_reconnect_success_total 1573
telemt_me_reader_eof_total 1578
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 20383
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1578
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 57961
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 467824440 (446.15 MB)
telemt_user_octets_to_client{user="hello"} 18486275948 (17.22 GB)
telemt_user_unique_ips_current{user="hello"} 21
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 18804.5 (5h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144396
telemt_connections_bad_total 72
telemt_handshake_timeouts_total 64443
telemt_upstream_connect_attempt_total 27476
telemt_upstream_connect_success_total 27306
telemt_upstream_connect_fail_total 81
telemt_upstream_connect_attempts_per_request{bucket="1"} 27306
telemt_upstream_connect_attempts_per_request{bucket="2"} 81
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11490
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 81
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 13996
telemt_me_reconnect_success_total 13995
telemt_me_reader_eof_total 14874
telemt_me_idle_close_by_peer_total 14873
telemt_me_route_drop_no_conn_total 41159
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 1993
telemt_me_writer_removed_unexpected_total 14879
telemt_me_writer_restored_same_endpoint_total 13971
telemt_me_writer_removed_unexpected_minus_restored_total 908
telemt_user_connections_total{user="hello"} 77055
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 390438664 (372.35 MB)
telemt_user_octets_to_client{user="hello"} 17173177352 (15.99 GB)
telemt_user_unique_ips_current{user="hello"} 23
```