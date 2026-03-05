# Server Metrics 2026-03-05 00:48:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.2.1

telemt_uptime_seconds 14077.1 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120089
telemt_connections_bad_total 9111
telemt_handshake_timeouts_total 821
telemt_upstream_connect_attempt_total 21300
telemt_upstream_connect_success_total 21117
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 21116
telemt_upstream_connect_attempts_per_request{bucket="2"} 60
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_keepalive_timeout_total 602
telemt_me_reconnect_attempts_total 10638
telemt_me_reconnect_success_total 10623
telemt_me_reader_eof_total 11050
telemt_me_idle_close_by_peer_total 11049
telemt_me_route_drop_no_conn_total 30632
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 134
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 54
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 69
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_force_close_total 1
telemt_me_writer_removed_unexpected_total 11109
telemt_me_writer_restored_same_endpoint_total 10603
telemt_me_writer_removed_unexpected_minus_restored_total 506
telemt_user_connections_total{user="hello"} 98357
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 2929934612 (2.73 GB)
telemt_user_octets_to_client{user="hello"} 53479326764 (49.81 GB)
telemt_user_unique_ips_current{user="hello"} 39
```

## server2

```
telemt 3.2.1

telemt_uptime_seconds 14071.8 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43283
telemt_connections_bad_total 794
telemt_handshake_timeouts_total 1054
telemt_upstream_connect_attempt_total 16166
telemt_upstream_connect_success_total 15842
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 15832
telemt_upstream_connect_attempts_per_request{bucket="2"} 74
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5233
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 104
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_timeout_total 1035
telemt_me_reconnect_attempts_total 6318
telemt_me_reconnect_success_total 6291
telemt_me_reader_eof_total 6395
telemt_me_idle_close_by_peer_total 6394
telemt_me_route_drop_no_conn_total 13221
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 63
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 138
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 85
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 1
telemt_pool_force_close_total 34
telemt_me_writer_removed_unexpected_total 6499
telemt_me_writer_restored_same_endpoint_total 6266
telemt_me_writer_removed_unexpected_minus_restored_total 233
telemt_user_connections_total{user="hello"} 39089
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 341367268 (325.55 MB)
telemt_user_octets_to_client{user="hello"} 10570417968 (9.84 GB)
telemt_user_unique_ips_current{user="hello"} 12
```

## server3

```
telemt 3.2.1

telemt_uptime_seconds 14068.6 (3h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 99967
telemt_connections_bad_total 1393
telemt_handshake_timeouts_total 702
telemt_upstream_connect_attempt_total 7014
telemt_upstream_connect_success_total 6956
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 6956
telemt_upstream_connect_attempts_per_request{bucket="2"} 21
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3640
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 549
telemt_me_reconnect_success_total 557
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 28452
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 53
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 43
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 4
telemt_pool_force_close_total 98
telemt_me_writer_removed_unexpected_total 549
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 91980
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 1086275360 (1.01 GB)
telemt_user_octets_to_client{user="hello"} 35318748920 (32.89 GB)
telemt_user_unique_ips_current{user="hello"} 16
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 46116.8 (12h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557978
telemt_connections_bad_total 82798
telemt_handshake_timeouts_total 14741
telemt_upstream_connect_attempt_total 21638
telemt_upstream_connect_success_total 21636
telemt_upstream_connect_attempts_per_request{bucket="1"} 21636
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9089
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 3157
telemt_me_reconnect_success_total 3136
telemt_me_reader_eof_total 3196
telemt_me_idle_close_by_peer_total 3196
telemt_me_route_drop_no_conn_total 187310
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 726
telemt_desync_full_logged_total 306
telemt_desync_suppressed_total 420
telemt_desync_frames_bucket_total{bucket="1_2"} 226
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 292
telemt_pool_swap_total 18
telemt_pool_force_close_total 507
telemt_pool_stale_pick_total 22
telemt_me_writer_removed_unexpected_total 3197
telemt_me_writer_restored_same_endpoint_total 3109
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 431903
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 5867144168 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 160304140904 (149.29 GB)
telemt_user_unique_ips_current{user="hello"} 19
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 46475.9 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 541084
telemt_connections_bad_total 3858
telemt_handshake_timeouts_total 5923
telemt_upstream_connect_attempt_total 29978
telemt_upstream_connect_success_total 29817
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 29817
telemt_upstream_connect_attempts_per_request{bucket="2"} 64
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 448
telemt_me_reconnect_attempts_total 6601
telemt_me_reconnect_success_total 6579
telemt_me_reader_eof_total 6824
telemt_me_idle_close_by_peer_total 6823
telemt_me_route_drop_no_conn_total 237975
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 842
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 538
telemt_desync_frames_bucket_total{bucket="1_2"} 170
telemt_desync_frames_bucket_total{bucket="3_10"} 354
telemt_desync_frames_bucket_total{bucket="gt_10"} 318
telemt_pool_swap_total 10
telemt_pool_force_close_total 420
telemt_pool_stale_pick_total 189
telemt_me_writer_removed_unexpected_total 6829
telemt_me_writer_restored_same_endpoint_total 6557
telemt_me_writer_removed_unexpected_minus_restored_total 272
telemt_user_connections_total{user="hello"} 490465
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 7395012988 (6.89 GB)
telemt_user_octets_to_client{user="hello"} 164028298376 (152.76 GB)
telemt_user_unique_ips_current{user="hello"} 26
```