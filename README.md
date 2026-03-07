# Server Metrics 2026-03-07 01:05:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.5

telemt_uptime_seconds 25060.5 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 309753
telemt_connections_bad_total 3690
telemt_handshake_timeouts_total 9425
telemt_upstream_connect_attempt_total 73931
telemt_upstream_connect_success_total 71884
telemt_upstream_connect_fail_total 1909
telemt_upstream_connect_attempts_per_request{bucket="1"} 73793
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45123
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 90
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 146
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1909
telemt_me_keepalive_timeout_total 1676
telemt_me_reconnect_attempts_total 43272
telemt_me_reconnect_success_total 41424
telemt_me_reader_eof_total 43990
telemt_me_idle_close_by_peer_total 43990
telemt_me_route_drop_no_conn_total 117788
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1008
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 734
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 454
telemt_desync_frames_bucket_total{bucket="gt_10"} 275
telemt_pool_swap_total 11
telemt_pool_force_close_total 540
telemt_pool_stale_pick_total 187
telemt_me_writer_removed_unexpected_total 44103
telemt_me_writer_restored_same_endpoint_total 41306
telemt_me_writer_restored_fallback_total 112
telemt_me_async_recovery_trigger_total 35814
telemt_me_writer_removed_unexpected_minus_restored_total 2685
telemt_user_connections_total{user="hello"} 281242
telemt_user_connections_current{user="hello"} 346
telemt_user_octets_from_client{user="hello"} 4284300620 (3.99 GB)
telemt_user_octets_to_client{user="hello"} 122499855304 (114.09 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## server2

```
telemt 3.3.5

telemt_uptime_seconds 25060.7 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 133132
telemt_connections_bad_total 118
telemt_handshake_timeouts_total 16197
telemt_upstream_connect_attempt_total 146924
telemt_upstream_connect_success_total 146921
telemt_upstream_connect_attempts_per_request{bucket="1"} 146921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38311
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 1245
telemt_me_reconnect_attempts_total 111220
telemt_me_reconnect_success_total 110924
telemt_me_reader_eof_total 101485
telemt_me_idle_close_by_peer_total 101480
telemt_me_route_drop_no_conn_total 42593
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 215
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 809
telemt_desync_full_logged_total 214
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 407
telemt_desync_frames_bucket_total{bucket="gt_10"} 262
telemt_pool_swap_total 17
telemt_pool_force_close_total 1102
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 101515
telemt_me_writer_restored_same_endpoint_total 110922
telemt_me_async_recovery_trigger_total 35807
telemt_user_connections_total{user="hello"} 110249
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 1568475980 (1.46 GB)
telemt_user_octets_to_client{user="hello"} 37972100284 (35.36 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## server3

```
telemt 3.3.5

telemt_uptime_seconds 25060.6 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239668
telemt_connections_bad_total 1243
telemt_handshake_timeouts_total 3596
telemt_upstream_connect_attempt_total 109353
telemt_upstream_connect_success_total 109175
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 109241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 71690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 2183
telemt_me_reconnect_attempts_total 78474
telemt_me_reconnect_success_total 78406
telemt_me_reader_eof_total 80086
telemt_me_idle_close_by_peer_total 80081
telemt_me_route_drop_no_conn_total 90061
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 205
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1045
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 778
telemt_desync_frames_bucket_total{bucket="1_2"} 198
telemt_desync_frames_bucket_total{bucket="3_10"} 429
telemt_desync_frames_bucket_total{bucket="gt_10"} 418
telemt_pool_swap_total 14
telemt_pool_force_close_total 372
telemt_pool_stale_pick_total 126
telemt_me_writer_removed_unexpected_total 80255
telemt_me_writer_restored_same_endpoint_total 78399
telemt_me_async_recovery_trigger_total 107216
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 223999
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 20605327476 (19.19 GB)
telemt_user_octets_to_client{user="hello"} 64091829264 (59.69 GB)
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## server4

```
telemt 3.3.5

telemt_uptime_seconds 25060.9 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244630
telemt_connections_bad_total 70575
telemt_handshake_timeouts_total 16940
telemt_upstream_connect_attempt_total 45039
telemt_upstream_connect_success_total 44954
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 44992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 868
telemt_me_reconnect_attempts_total 14503
telemt_me_reconnect_success_total 14476
telemt_me_reader_eof_total 19739
telemt_me_idle_close_by_peer_total 19737
telemt_me_route_drop_no_conn_total 65244
telemt_me_single_endpoint_shadow_rotate_total 208
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 218
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 13
telemt_pool_force_close_total 453
telemt_pool_stale_pick_total 474
telemt_me_writer_removed_unexpected_total 19744
telemt_me_writer_restored_same_endpoint_total 14471
telemt_me_writer_removed_unexpected_minus_restored_total 5273
telemt_user_connections_total{user="hello"} 153085
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 1738338636 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 49833444400 (46.41 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## server5

```
telemt 3.3.5

telemt_uptime_seconds 25059.3 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210187
telemt_connections_bad_total 510
telemt_handshake_timeouts_total 2502
telemt_upstream_connect_attempt_total 41898
telemt_upstream_connect_success_total 41743
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 41763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 1164
telemt_me_reconnect_attempts_total 12475
telemt_me_reconnect_success_total 12441
telemt_me_reader_eof_total 17052
telemt_me_idle_close_by_peer_total 17050
telemt_me_route_drop_no_conn_total 70314
telemt_me_route_drop_channel_closed_total 4
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 204
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 799
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 593
telemt_desync_frames_bucket_total{bucket="1_2"} 273
telemt_desync_frames_bucket_total{bucket="3_10"} 263
telemt_desync_frames_bucket_total{bucket="gt_10"} 263
telemt_pool_swap_total 14
telemt_pool_force_close_total 428
telemt_pool_stale_pick_total 215
telemt_me_writer_removed_unexpected_total 17119
telemt_me_writer_restored_same_endpoint_total 12433
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 4682
telemt_user_connections_total{user="hello"} 192876
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 10192945088 (9.49 GB)
telemt_user_octets_to_client{user="hello"} 67881881388 (63.22 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 24
```