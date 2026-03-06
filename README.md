# Server Metrics 2026-03-06 02:30:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.2

telemt_uptime_seconds 14925.8 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99597
telemt_connections_bad_total 15904
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 12990
telemt_upstream_connect_success_total 12874
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 12874
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5126
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 136
telemt_me_reconnect_attempts_total 3624
telemt_me_reconnect_success_total 3608
telemt_me_reader_eof_total 3736
telemt_me_idle_close_by_peer_total 3736
telemt_me_route_drop_no_conn_total 25564
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 65
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 158
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 89
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_pool_force_close_total 90
telemt_me_writer_removed_unexpected_total 3736
telemt_me_writer_restored_same_endpoint_total 3602
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 78675
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 919980148 (877.36 MB)
telemt_user_octets_to_client{user="hello"} 28959010832 (26.97 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## server2

```
telemt 3.3.2

telemt_uptime_seconds 14921.2 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 33177
telemt_connections_bad_total 43
telemt_handshake_timeouts_total 423
telemt_upstream_connect_attempt_total 10624
telemt_upstream_connect_success_total 10622
telemt_upstream_connect_attempts_per_request{bucket="1"} 10622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 142
telemt_me_reconnect_attempts_total 1696
telemt_me_reconnect_success_total 1688
telemt_me_reader_eof_total 1705
telemt_me_idle_close_by_peer_total 1705
telemt_me_route_drop_no_conn_total 9671
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 60
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 6
telemt_pool_force_close_total 69
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 1706
telemt_me_writer_restored_same_endpoint_total 1682
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 32179
telemt_user_connections_current{user="hello"} 91
telemt_user_octets_from_client{user="hello"} 201524204 (192.19 MB)
telemt_user_octets_to_client{user="hello"} 7043741128 (6.56 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## server3

```
telemt 3.3.2

telemt_uptime_seconds 14918.8 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59988
telemt_connections_bad_total 532
telemt_handshake_timeouts_total 589
telemt_upstream_connect_attempt_total 13684
telemt_upstream_connect_success_total 13565
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 13565
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7903
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 4035
telemt_me_reconnect_success_total 4022
telemt_me_reader_eof_total 4214
telemt_me_idle_close_by_peer_total 4214
telemt_me_route_drop_no_conn_total 16900
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 127
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 86
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 3
telemt_pool_force_close_total 85
telemt_me_writer_removed_unexpected_total 4215
telemt_me_writer_restored_same_endpoint_total 4015
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 56459
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 597336132 (569.66 MB)
telemt_user_octets_to_client{user="hello"} 20266740656 (18.87 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## server4

```
telemt 3.3.2

telemt_uptime_seconds 14915.3 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47621
telemt_connections_bad_total 263
telemt_handshake_timeouts_total 2921
telemt_upstream_connect_attempt_total 9951
telemt_upstream_connect_success_total 9922
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 9922
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 2077
telemt_me_reconnect_success_total 2064
telemt_me_reader_eof_total 2158
telemt_me_idle_close_by_peer_total 2158
telemt_me_route_drop_no_conn_total 19054
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 144
telemt_desync_full_logged_total 61
telemt_desync_suppressed_total 83
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 73
telemt_pool_swap_total 6
telemt_pool_force_close_total 116
telemt_me_writer_removed_unexpected_total 2158
telemt_me_writer_restored_same_endpoint_total 2057
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 41954
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 372743496 (355.48 MB)
telemt_user_octets_to_client{user="hello"} 20744766296 (19.32 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## server5

```
telemt 3.3.2

telemt_uptime_seconds 14914.2 (4h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59575
telemt_connections_bad_total 584
telemt_handshake_timeouts_total 401
telemt_upstream_connect_attempt_total 8884
telemt_upstream_connect_success_total 8863
telemt_upstream_connect_attempts_per_request{bucket="1"} 8863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3281
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1025
telemt_me_reconnect_success_total 1021
telemt_me_reader_eof_total 1041
telemt_me_idle_close_by_peer_total 1041
telemt_me_route_drop_no_conn_total 18367
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 53
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 6
telemt_pool_force_close_total 92
telemt_me_writer_removed_unexpected_total 1041
telemt_me_writer_restored_same_endpoint_total 1015
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 57718
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 11981807800 (11.16 GB)
telemt_user_octets_to_client{user="hello"} 23446086832 (21.84 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```