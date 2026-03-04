# Server Metrics 2026-03-04 02:34:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 19425.4 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 124161
telemt_connections_bad_total 1379
telemt_handshake_timeouts_total 1043
telemt_upstream_connect_attempt_total 15661
telemt_upstream_connect_success_total 15591
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 15591
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 4067
telemt_me_reconnect_success_total 4060
telemt_me_reader_eof_total 4152
telemt_me_idle_close_by_peer_total 4152
telemt_me_route_drop_no_conn_total 44436
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 218
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 83
telemt_pool_swap_total 3
telemt_pool_force_close_total 115
telemt_me_writer_removed_unexpected_total 4152
telemt_me_writer_restored_same_endpoint_total 4040
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 118988
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 955889564 (911.61 MB)
telemt_user_octets_to_client{user="hello"} 35266459160 (32.84 GB)
telemt_user_unique_ips_current{user="hello"} 54
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 19422.1 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58391
telemt_connections_bad_total 277
telemt_handshake_timeouts_total 15139
telemt_upstream_connect_attempt_total 45805
telemt_upstream_connect_success_total 45291
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 45285
telemt_upstream_connect_attempts_per_request{bucket="2"} 246
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30862
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_keepalive_timeout_total 813
telemt_me_reconnect_attempts_total 27981
telemt_me_reconnect_success_total 27964
telemt_me_reader_eof_total 28680
telemt_me_idle_close_by_peer_total 28679
telemt_me_route_drop_no_conn_total 19510
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 90
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 52
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_me_writer_removed_unexpected_total 28741
telemt_me_writer_restored_same_endpoint_total 27944
telemt_me_writer_removed_unexpected_minus_restored_total 797
telemt_user_connections_total{user="hello"} 42293
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 333251240 (317.81 MB)
telemt_user_octets_to_client{user="hello"} 23666163768 (22.04 GB)
telemt_user_unique_ips_current{user="hello"} 18
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 19420.9 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137807
telemt_connections_bad_total 49246
telemt_handshake_timeouts_total 3240
telemt_upstream_connect_attempt_total 22787
telemt_upstream_connect_success_total 22636
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 22636
telemt_upstream_connect_attempts_per_request{bucket="2"} 70
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9231
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 73
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 285
telemt_me_reconnect_attempts_total 7797
telemt_me_reconnect_success_total 7783
telemt_me_reader_eof_total 8103
telemt_me_idle_close_by_peer_total 8101
telemt_me_route_drop_no_conn_total 26678
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 277
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 181
telemt_desync_frames_bucket_total{bucket="1_2"} 58
telemt_desync_frames_bucket_total{bucket="3_10"} 102
telemt_desync_frames_bucket_total{bucket="gt_10"} 117
telemt_pool_swap_total 2
telemt_pool_force_close_total 62
telemt_me_writer_removed_unexpected_total 8104
telemt_me_writer_restored_same_endpoint_total 7762
telemt_me_writer_removed_unexpected_minus_restored_total 342
telemt_user_connections_total{user="hello"} 81998
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 497854328 (474.79 MB)
telemt_user_octets_to_client{user="hello"} 20260253404 (18.87 GB)
telemt_user_unique_ips_current{user="hello"} 24
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 19419.9 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61749
telemt_connections_bad_total 191
telemt_handshake_timeouts_total 648
telemt_upstream_connect_attempt_total 12083
telemt_upstream_connect_success_total 12022
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 12022
telemt_upstream_connect_attempts_per_request{bucket="2"} 30
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7494
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 1628
telemt_me_reconnect_success_total 1633
telemt_me_reader_eof_total 1639
telemt_me_idle_close_by_peer_total 1639
telemt_me_route_drop_no_conn_total 21295
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 21
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 6
telemt_pool_force_close_total 139
telemt_me_writer_removed_unexpected_total 1639
telemt_me_writer_restored_same_endpoint_total 1613
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 59799
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 491354864 (468.59 MB)
telemt_user_octets_to_client{user="hello"} 19231328088 (17.91 GB)
telemt_user_unique_ips_current{user="hello"} 27
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 19418.6 (5h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148657
telemt_connections_bad_total 83
telemt_handshake_timeouts_total 66781
telemt_upstream_connect_attempt_total 28415
telemt_upstream_connect_success_total 28239
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 28239
telemt_upstream_connect_attempts_per_request{bucket="2"} 84
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16351
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11824
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 381
telemt_me_reconnect_attempts_total 14352
telemt_me_reconnect_success_total 14351
telemt_me_reader_eof_total 15249
telemt_me_idle_close_by_peer_total 15248
telemt_me_route_drop_no_conn_total 41750
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 84
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 106
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 81
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 51
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 2
telemt_pool_force_close_total 59
telemt_pool_stale_pick_total 2116
telemt_me_writer_removed_unexpected_total 15254
telemt_me_writer_restored_same_endpoint_total 14327
telemt_me_writer_removed_unexpected_minus_restored_total 927
telemt_user_connections_total{user="hello"} 78923
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 396800768 (378.42 MB)
telemt_user_octets_to_client{user="hello"} 17640573488 (16.43 GB)
telemt_user_unique_ips_current{user="hello"} 17
```