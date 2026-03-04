# Server Metrics 2026-03-04 14:16:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 61550.8 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1124635
telemt_connections_bad_total 13927
telemt_handshake_timeouts_total 19917
telemt_upstream_connect_attempt_total 37032
telemt_upstream_connect_success_total 36865
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 36865
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 425
telemt_me_reconnect_attempts_total 8164
telemt_me_reconnect_success_total 8105
telemt_me_reader_eof_total 8369
telemt_me_idle_close_by_peer_total 8368
telemt_me_route_drop_no_conn_total 417010
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 242
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1978
telemt_desync_full_logged_total 657
telemt_desync_suppressed_total 1321
telemt_desync_frames_bucket_total{bucket="1_2"} 580
telemt_desync_frames_bucket_total{bucket="3_10"} 750
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 16
telemt_pool_force_close_total 682
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8369
telemt_me_writer_restored_same_endpoint_total 8083
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 895171
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 11383052096 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 301578393440 (280.87 GB)
telemt_user_unique_ips_current{user="hello"} 138
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 61547.2 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 429058
telemt_connections_bad_total 3653
telemt_handshake_timeouts_total 29524
telemt_upstream_connect_attempt_total 110657
telemt_upstream_connect_success_total 108987
telemt_upstream_connect_fail_total 797
telemt_upstream_connect_attempts_per_request{bucket="1"} 108981
telemt_upstream_connect_attempts_per_request{bucket="2"} 803
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 797
telemt_me_keepalive_timeout_total 1488
telemt_me_reconnect_attempts_total 60607
telemt_me_reconnect_success_total 60511
telemt_me_reader_eof_total 62105
telemt_me_idle_close_by_peer_total 62104
telemt_me_route_drop_no_conn_total 174749
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 258
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 862
telemt_desync_full_logged_total 266
telemt_desync_suppressed_total 596
telemt_desync_frames_bucket_total{bucket="1_2"} 166
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 341
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 62185
telemt_me_writer_restored_same_endpoint_total 60486
telemt_me_writer_removed_unexpected_minus_restored_total 1699
telemt_user_connections_total{user="hello"} 333554
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 4248245820 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 105653479332 (98.40 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 61546.0 (17h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 849991
telemt_connections_bad_total 183010
telemt_handshake_timeouts_total 29229
telemt_upstream_connect_attempt_total 83682
telemt_upstream_connect_success_total 83157
telemt_upstream_connect_fail_total 253
telemt_upstream_connect_attempts_per_request{bucket="1"} 83156
telemt_upstream_connect_attempts_per_request{bucket="2"} 254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33811
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 253
telemt_me_keepalive_timeout_total 1090
telemt_me_reconnect_attempts_total 37969
telemt_me_reconnect_success_total 37870
telemt_me_reader_eof_total 39867
telemt_me_idle_close_by_peer_total 39863
telemt_me_route_drop_no_conn_total 310462
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1750
telemt_desync_full_logged_total 588
telemt_desync_suppressed_total 1162
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 564
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39879
telemt_me_writer_restored_same_endpoint_total 37848
telemt_me_writer_removed_unexpected_minus_restored_total 2031
telemt_user_connections_total{user="hello"} 599582
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 12545387004 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 203778460088 (189.78 GB)
telemt_user_unique_ips_current{user="hello"} 64
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 8223.3 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105304
telemt_connections_bad_total 10819
telemt_handshake_timeouts_total 2981
telemt_upstream_connect_attempt_total 4448
telemt_upstream_connect_success_total 4448
telemt_upstream_connect_attempts_per_request{bucket="1"} 4448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1726
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 848
telemt_me_reconnect_success_total 860
telemt_me_reader_eof_total 867
telemt_me_idle_close_by_peer_total 867
telemt_me_route_drop_no_conn_total 39582
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 153
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 90
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 2
telemt_pool_force_close_total 41
telemt_me_writer_removed_unexpected_total 867
telemt_me_writer_restored_same_endpoint_total 839
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 89657
telemt_user_connections_current{user="hello"} 459
telemt_user_octets_from_client{user="hello"} 1443440408 (1.34 GB)
telemt_user_octets_to_client{user="hello"} 52252904068 (48.66 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 8582.7 (2h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148648
telemt_connections_bad_total 1142
telemt_handshake_timeouts_total 2560
telemt_upstream_connect_attempt_total 5278
telemt_upstream_connect_success_total 5251
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 5251
telemt_upstream_connect_attempts_per_request{bucket="2"} 13
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2160
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 1210
telemt_me_reconnect_success_total 1220
telemt_me_reader_eof_total 1243
telemt_me_idle_close_by_peer_total 1243
telemt_me_route_drop_no_conn_total 51921
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 419
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 268
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 174
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 1
telemt_pool_force_close_total 53
telemt_me_writer_removed_unexpected_total 1243
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 127871
telemt_user_connections_current{user="hello"} 564
telemt_user_octets_from_client{user="hello"} 1462764272 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 36001995736 (33.53 GB)
telemt_user_unique_ips_current{user="hello"} 54
```