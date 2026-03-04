# Server Metrics 2026-03-04 16:14:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 68622.4 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1314243
telemt_connections_bad_total 18515
telemt_handshake_timeouts_total 22824
telemt_upstream_connect_attempt_total 39918
telemt_upstream_connect_success_total 39731
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 39731
telemt_upstream_connect_attempts_per_request{bucket="2"} 73
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 452
telemt_me_reconnect_attempts_total 8458
telemt_me_reconnect_success_total 8391
telemt_me_reader_eof_total 8667
telemt_me_idle_close_by_peer_total 8666
telemt_me_route_drop_no_conn_total 504031
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 269
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2791
telemt_desync_full_logged_total 886
telemt_desync_suppressed_total 1905
telemt_desync_frames_bucket_total{bucket="1_2"} 803
telemt_desync_frames_bucket_total{bucket="3_10"} 1047
telemt_desync_frames_bucket_total{bucket="gt_10"} 941
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8667
telemt_me_writer_restored_same_endpoint_total 8369
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 1067156
telemt_user_connections_current{user="hello"} 1071
telemt_user_octets_from_client{user="hello"} 14174473516 (13.20 GB)
telemt_user_octets_to_client{user="hello"} 357014678608 (332.50 GB)
telemt_user_unique_ips_current{user="hello"} 110
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 68618.9 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 499103
telemt_connections_bad_total 4323
telemt_handshake_timeouts_total 30641
telemt_upstream_connect_attempt_total 124084
telemt_upstream_connect_success_total 122330
telemt_upstream_connect_fail_total 839
telemt_upstream_connect_attempts_per_request{bucket="1"} 122324
telemt_upstream_connect_attempts_per_request{bucket="2"} 845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 79172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43134
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 839
telemt_me_keepalive_timeout_total 1632
telemt_me_reconnect_attempts_total 67709
telemt_me_reconnect_success_total 67602
telemt_me_reader_eof_total 69339
telemt_me_idle_close_by_peer_total 69338
telemt_me_route_drop_no_conn_total 204303
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 287
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1294
telemt_desync_full_logged_total 390
telemt_desync_suppressed_total 904
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 510
telemt_desync_frames_bucket_total{bucket="gt_10"} 543
telemt_pool_swap_total 5
telemt_pool_force_close_total 379
telemt_pool_stale_pick_total 124
telemt_me_writer_removed_unexpected_total 69419
telemt_me_writer_restored_same_endpoint_total 67576
telemt_me_writer_removed_unexpected_minus_restored_total 1843
telemt_user_connections_total{user="hello"} 399822
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 6056864388 (5.64 GB)
telemt_user_octets_to_client{user="hello"} 125869605656 (117.23 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 68617.5 (19h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1008506
telemt_connections_bad_total 203024
telemt_handshake_timeouts_total 30286
telemt_upstream_connect_attempt_total 90110
telemt_upstream_connect_success_total 89492
telemt_upstream_connect_fail_total 299
telemt_upstream_connect_attempts_per_request{bucket="1"} 89491
telemt_upstream_connect_attempts_per_request{bucket="2"} 300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52739
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 299
telemt_me_keepalive_timeout_total 1175
telemt_me_reconnect_attempts_total 40244
telemt_me_reconnect_success_total 40137
telemt_me_reader_eof_total 42261
telemt_me_idle_close_by_peer_total 42256
telemt_me_route_drop_no_conn_total 368250
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_shadow_rotate_total 282
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2111
telemt_desync_full_logged_total 700
telemt_desync_suppressed_total 1411
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 682
telemt_desync_frames_bucket_total{bucket="gt_10"} 797
telemt_pool_swap_total 8
telemt_pool_force_close_total 453
telemt_me_writer_removed_unexpected_total 42274
telemt_me_writer_restored_same_endpoint_total 40115
telemt_me_writer_removed_unexpected_minus_restored_total 2159
telemt_user_connections_total{user="hello"} 728596
telemt_user_connections_current{user="hello"} 683
telemt_user_octets_from_client{user="hello"} 14386812136 (13.40 GB)
telemt_user_octets_to_client{user="hello"} 249306188960 (232.18 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 15294.9 (4h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250007
telemt_connections_bad_total 29291
telemt_handshake_timeouts_total 6439
telemt_upstream_connect_attempt_total 6226
telemt_upstream_connect_success_total 6226
telemt_upstream_connect_attempts_per_request{bucket="1"} 6226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2707
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 870
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 82370
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 240
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 150
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 4
telemt_pool_force_close_total 146
telemt_me_writer_removed_unexpected_total 888
telemt_me_writer_restored_same_endpoint_total 857
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 205429
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 2693056384 (2.51 GB)
telemt_user_octets_to_client{user="hello"} 78235630504 (72.86 GB)
telemt_user_unique_ips_current{user="hello"} 48
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 15654.4 (4h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269373
telemt_connections_bad_total 2521
telemt_handshake_timeouts_total 3998
telemt_upstream_connect_attempt_total 7652
telemt_upstream_connect_success_total 7613
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7613
telemt_upstream_connect_attempts_per_request{bucket="2"} 19
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4395
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3207
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1331
telemt_me_reconnect_success_total 1338
telemt_me_reader_eof_total 1364
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 104149
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 64
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 535
telemt_desync_full_logged_total 210
telemt_desync_suppressed_total 325
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 234
telemt_desync_frames_bucket_total{bucket="gt_10"} 221
telemt_pool_swap_total 4
telemt_pool_force_close_total 184
telemt_me_writer_removed_unexpected_total 1364
telemt_me_writer_restored_same_endpoint_total 1317
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 231444
telemt_user_connections_current{user="hello"} 623
telemt_user_octets_from_client{user="hello"} 3752962876 (3.50 GB)
telemt_user_octets_to_client{user="hello"} 69300183320 (64.54 GB)
telemt_user_unique_ips_current{user="hello"} 55
```