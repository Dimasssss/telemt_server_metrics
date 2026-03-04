# Server Metrics 2026-03-04 12:03:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 53555.4 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889524
telemt_connections_bad_total 12089
telemt_handshake_timeouts_total 13291
telemt_upstream_connect_attempt_total 32644
telemt_upstream_connect_success_total 32505
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 32505
telemt_upstream_connect_attempts_per_request{bucket="2"} 59
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17943
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 364
telemt_me_reconnect_attempts_total 7088
telemt_me_reconnect_success_total 7040
telemt_me_reader_eof_total 7260
telemt_me_idle_close_by_peer_total 7260
telemt_me_route_drop_no_conn_total 332485
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 211
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1431
telemt_desync_full_logged_total 489
telemt_desync_suppressed_total 942
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 550
telemt_desync_frames_bucket_total{bucket="gt_10"} 473
telemt_pool_swap_total 14
telemt_pool_force_close_total 543
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 7260
telemt_me_writer_restored_same_endpoint_total 7019
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 710645
telemt_user_connections_current{user="hello"} 960
telemt_user_octets_from_client{user="hello"} 7610982396 (7.09 GB)
telemt_user_octets_to_client{user="hello"} 216198502188 (201.35 GB)
telemt_user_unique_ips_current{user="hello"} 101
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 53551.9 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 356508
telemt_connections_bad_total 3116
telemt_handshake_timeouts_total 27636
telemt_upstream_connect_attempt_total 101197
telemt_upstream_connect_success_total 99643
telemt_upstream_connect_fail_total 738
telemt_upstream_connect_attempts_per_request{bucket="1"} 99637
telemt_upstream_connect_attempts_per_request{bucket="2"} 744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32991
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 738
telemt_me_keepalive_timeout_total 1405
telemt_me_reconnect_attempts_total 56967
telemt_me_reconnect_success_total 56879
telemt_me_reader_eof_total 58316
telemt_me_idle_close_by_peer_total 58315
telemt_me_route_drop_no_conn_total 146757
telemt_me_hardswap_pending_ttl_expired_total 16
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 226
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 643
telemt_desync_full_logged_total 222
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 130
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 4
telemt_pool_force_close_total 280
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 58396
telemt_me_writer_restored_same_endpoint_total 56854
telemt_me_writer_removed_unexpected_minus_restored_total 1542
telemt_user_connections_total{user="hello"} 266980
telemt_user_connections_current{user="hello"} 411
telemt_user_octets_from_client{user="hello"} 3508267032 (3.27 GB)
telemt_user_octets_to_client{user="hello"} 84331129956 (78.54 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 53550.7 (14h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 674946
telemt_connections_bad_total 160286
telemt_handshake_timeouts_total 21595
telemt_upstream_connect_attempt_total 79172
telemt_upstream_connect_success_total 78702
telemt_upstream_connect_fail_total 225
telemt_upstream_connect_attempts_per_request{bucket="1"} 78701
telemt_upstream_connect_attempts_per_request{bucket="2"} 226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46224
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 225
telemt_me_keepalive_timeout_total 1027
telemt_me_reconnect_attempts_total 37024
telemt_me_reconnect_success_total 36932
telemt_me_reader_eof_total 38904
telemt_me_idle_close_by_peer_total 38900
telemt_me_route_drop_no_conn_total 252621
telemt_me_hardswap_pending_ttl_expired_total 15
telemt_me_single_endpoint_shadow_rotate_total 224
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1172
telemt_desync_full_logged_total 421
telemt_desync_suppressed_total 751
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 395
telemt_desync_frames_bucket_total{bucket="gt_10"} 432
telemt_pool_swap_total 5
telemt_pool_force_close_total 294
telemt_me_writer_removed_unexpected_total 38916
telemt_me_writer_restored_same_endpoint_total 36910
telemt_me_writer_removed_unexpected_minus_restored_total 2006
telemt_user_connections_total{user="hello"} 469724
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 8571160216 (7.98 GB)
telemt_user_octets_to_client{user="hello"} 156803564888 (146.03 GB)
telemt_user_unique_ips_current{user="hello"} 72
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 228.1 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2929
telemt_connections_bad_total 200
telemt_handshake_timeouts_total 21
telemt_upstream_connect_attempt_total 102
telemt_upstream_connect_success_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 102
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33
telemt_me_reconnect_success_total 21
telemt_me_route_drop_no_conn_total 607
telemt_me_single_endpoint_shadow_rotate_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 4
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 3
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_force_close_total 1
telemt_user_connections_total{user="hello"} 2585
telemt_user_connections_current{user="hello"} 429
telemt_user_octets_from_client{user="hello"} 15939756 (15.20 MB)
telemt_user_octets_to_client{user="hello"} 1220334524 (1.14 GB)
telemt_user_unique_ips_current{user="hello"} 51
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 587.6 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10323
telemt_handshake_timeouts_total 106
telemt_upstream_connect_attempt_total 118
telemt_upstream_connect_success_total 115
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 115
telemt_upstream_connect_attempts_per_request{bucket="2"} 1
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 57
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 3
telemt_me_reconnect_success_total 20
telemt_me_route_drop_no_conn_total 2715
telemt_me_single_endpoint_shadow_rotate_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 30
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 7
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_user_connections_total{user="hello"} 9098
telemt_user_connections_current{user="hello"} 710
telemt_user_octets_from_client{user="hello"} 51221916 (48.85 MB)
telemt_user_octets_to_client{user="hello"} 2820344928 (2.63 GB)
telemt_user_unique_ips_current{user="hello"} 61
```