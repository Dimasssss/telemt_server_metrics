# Server Metrics 2026-03-04 14:42:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 63087.4 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1164543
telemt_connections_bad_total 14018
telemt_handshake_timeouts_total 21551
telemt_upstream_connect_attempt_total 37437
telemt_upstream_connect_success_total 37270
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37270
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20514
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16681
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 429
telemt_me_reconnect_attempts_total 8175
telemt_me_reconnect_success_total 8114
telemt_me_reader_eof_total 8379
telemt_me_idle_close_by_peer_total 8378
telemt_me_route_drop_no_conn_total 430530
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 247
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2179
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1467
telemt_desync_frames_bucket_total{bucket="1_2"} 646
telemt_desync_frames_bucket_total{bucket="3_10"} 826
telemt_desync_frames_bucket_total{bucket="gt_10"} 707
telemt_pool_swap_total 17
telemt_pool_force_close_total 682
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8379
telemt_me_writer_restored_same_endpoint_total 8092
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 931632
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 12402215612 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 312764736056 (291.28 GB)
telemt_user_unique_ips_current{user="hello"} 103
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 63083.9 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 442574
telemt_connections_bad_total 3751
telemt_handshake_timeouts_total 29830
telemt_upstream_connect_attempt_total 113605
telemt_upstream_connect_success_total 111929
telemt_upstream_connect_fail_total 800
telemt_upstream_connect_attempts_per_request{bucket="1"} 111923
telemt_upstream_connect_attempts_per_request{bucket="2"} 806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 800
telemt_me_keepalive_timeout_total 1512
telemt_me_reconnect_attempts_total 62090
telemt_me_reconnect_success_total 61992
telemt_me_reader_eof_total 63618
telemt_me_idle_close_by_peer_total 63617
telemt_me_route_drop_no_conn_total 180232
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 992
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 191
telemt_desync_frames_bucket_total{bucket="3_10"} 414
telemt_desync_frames_bucket_total{bucket="gt_10"} 387
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 63698
telemt_me_writer_restored_same_endpoint_total 61967
telemt_me_writer_removed_unexpected_minus_restored_total 1731
telemt_user_connections_total{user="hello"} 346293
telemt_user_connections_current{user="hello"} 432
telemt_user_octets_from_client{user="hello"} 5222560540 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 110047772532 (102.49 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 63082.7 (17h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 887955
telemt_connections_bad_total 187330
telemt_handshake_timeouts_total 29504
telemt_upstream_connect_attempt_total 84536
telemt_upstream_connect_success_total 83996
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 83995
telemt_upstream_connect_attempts_per_request{bucket="2"} 261
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34119
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 224
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_timeout_total 1097
telemt_me_reconnect_attempts_total 38086
telemt_me_reconnect_success_total 37987
telemt_me_reader_eof_total 39985
telemt_me_idle_close_by_peer_total 39981
telemt_me_route_drop_no_conn_total 322935
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_single_endpoint_shadow_rotate_total 259
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1850
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1237
telemt_desync_frames_bucket_total{bucket="1_2"} 590
telemt_desync_frames_bucket_total{bucket="3_10"} 589
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 39997
telemt_me_writer_restored_same_endpoint_total 37965
telemt_me_writer_removed_unexpected_minus_restored_total 2032
telemt_user_connections_total{user="hello"} 627457
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 12766446060 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 214007196504 (199.31 GB)
telemt_user_unique_ips_current{user="hello"} 67
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 9760.3 (2h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 137496
telemt_connections_bad_total 13237
telemt_handshake_timeouts_total 4659
telemt_upstream_connect_attempt_total 4654
telemt_upstream_connect_success_total 4654
telemt_upstream_connect_attempts_per_request{bucket="1"} 4654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1793
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 47458
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 173
telemt_desync_full_logged_total 68
telemt_desync_suppressed_total 105
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 116103
telemt_user_connections_current{user="hello"} 535
telemt_user_octets_from_client{user="hello"} 1660689176 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 58116690460 (54.13 GB)
telemt_user_unique_ips_current{user="hello"} 52
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 10119.5 (2h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174401
telemt_connections_bad_total 1856
telemt_handshake_timeouts_total 2799
telemt_upstream_connect_attempt_total 5720
telemt_upstream_connect_success_total 5691
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5691
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 1232
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 63093
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 448
telemt_desync_full_logged_total 168
telemt_desync_suppressed_total 280
telemt_desync_frames_bucket_total{bucket="1_2"} 57
telemt_desync_frames_bucket_total{bucket="3_10"} 194
telemt_desync_frames_bucket_total{bucket="gt_10"} 197
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 150627
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 1672743752 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 41070216840 (38.25 GB)
telemt_user_unique_ips_current{user="hello"} 60
```