# Server Metrics 2026-03-06 14:22:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 14457.8 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431101
telemt_connections_bad_total 1841
telemt_handshake_timeouts_total 2321
telemt_upstream_connect_attempt_total 7981
telemt_upstream_connect_success_total 7933
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 7951
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 97
telemt_me_reconnect_attempts_total 1812
telemt_me_reconnect_success_total 1803
telemt_me_reader_eof_total 1896
telemt_me_idle_close_by_peer_total 1896
telemt_me_route_drop_no_conn_total 153239
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2360
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 1788
telemt_desync_frames_bucket_total{bucket="1_2"} 553
telemt_desync_frames_bucket_total{bucket="3_10"} 803
telemt_desync_frames_bucket_total{bucket="gt_10"} 1004
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1898
telemt_me_writer_restored_same_endpoint_total 1797
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 363990
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 10503112268 (9.78 GB)
telemt_user_octets_to_client{user="hello"} 149136235056 (138.89 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 14457.4 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164291
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 5257
telemt_upstream_connect_attempt_total 6230
telemt_upstream_connect_success_total 6214
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6230
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3298
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 599
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 630
telemt_me_idle_close_by_peer_total 630
telemt_me_route_drop_no_conn_total 81743
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 610
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 410
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 281
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_restored_same_endpoint_total 591
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 150237
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 1652394704 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 69573475336 (64.80 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 14457.1 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 341527
telemt_connections_bad_total 5122
telemt_handshake_timeouts_total 35354
telemt_upstream_connect_attempt_total 10450
telemt_upstream_connect_success_total 10402
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 10443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5578
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 3015
telemt_me_reconnect_success_total 3002
telemt_me_reader_eof_total 3180
telemt_me_idle_close_by_peer_total 3180
telemt_me_route_drop_no_conn_total 162045
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 595
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 3182
telemt_me_writer_restored_same_endpoint_total 2997
telemt_me_writer_removed_unexpected_minus_restored_total 185
telemt_user_connections_total{user="hello"} 289260
telemt_user_connections_current{user="hello"} 620
telemt_user_octets_from_client{user="hello"} 3018693500 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 91524589048 (85.24 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 13773.5 (3h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240033
telemt_connections_bad_total 44095
telemt_handshake_timeouts_total 7886
telemt_upstream_connect_attempt_total 6743
telemt_upstream_connect_success_total 6743
telemt_upstream_connect_attempts_per_request{bucket="1"} 6743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2811
telemt_me_keepalive_timeout_total 80
telemt_me_reconnect_attempts_total 908
telemt_me_reconnect_success_total 897
telemt_me_reader_eof_total 910
telemt_me_idle_close_by_peer_total 910
telemt_me_route_drop_no_conn_total 85663
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 251
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 161
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 910
telemt_me_writer_restored_same_endpoint_total 897
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 154920
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 1863381860 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 59166616732 (55.10 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 14457.7 (4h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 260266
telemt_connections_bad_total 7893
telemt_handshake_timeouts_total 2531
telemt_upstream_connect_attempt_total 6608
telemt_upstream_connect_success_total 6598
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3602
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2955
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 1189
telemt_me_reconnect_success_total 1178
telemt_me_reader_eof_total 1228
telemt_me_idle_close_by_peer_total 1227
telemt_me_route_drop_no_conn_total 138565
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 427
telemt_desync_full_logged_total 148
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 194
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1232
telemt_me_writer_restored_same_endpoint_total 1177
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 237213
telemt_user_connections_current{user="hello"} 556
telemt_user_octets_from_client{user="hello"} 14195616796 (13.22 GB)
telemt_user_octets_to_client{user="hello"} 135578300912 (126.27 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 96
```