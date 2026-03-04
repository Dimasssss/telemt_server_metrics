# Server Metrics 2026-03-04 07:16:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 36332.1 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387227
telemt_connections_bad_total 6105
telemt_handshake_timeouts_total 5906
telemt_upstream_connect_attempt_total 23320
telemt_upstream_connect_success_total 23209
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 23209
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13157
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 243
telemt_me_reconnect_attempts_total 4695
telemt_me_reconnect_success_total 4668
telemt_me_reader_eof_total 4778
telemt_me_idle_close_by_peer_total 4778
telemt_me_route_drop_no_conn_total 127224
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 146
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 757
telemt_desync_full_logged_total 287
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 223
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 8
telemt_pool_force_close_total 300
telemt_me_writer_removed_unexpected_total 4778
telemt_me_writer_restored_same_endpoint_total 4648
telemt_me_writer_removed_unexpected_minus_restored_total 130
telemt_user_connections_total{user="hello"} 320442
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 3673472108 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 98136926732 (91.40 GB)
telemt_user_unique_ips_current{user="hello"} 77
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 36328.7 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165085
telemt_connections_bad_total 1251
telemt_handshake_timeouts_total 22969
telemt_upstream_connect_attempt_total 74805
telemt_upstream_connect_success_total 73709
telemt_upstream_connect_fail_total 509
telemt_upstream_connect_attempts_per_request{bucket="1"} 73703
telemt_upstream_connect_attempts_per_request{bucket="2"} 515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49920
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23767
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 509
telemt_me_keepalive_timeout_total 1173
telemt_me_reconnect_attempts_total 43809
telemt_me_reconnect_success_total 43734
telemt_me_reader_eof_total 44818
telemt_me_idle_close_by_peer_total 44817
telemt_me_route_drop_no_conn_total 59352
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 304
telemt_desync_full_logged_total 105
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 158
telemt_desync_frames_bucket_total{bucket="gt_10"} 77
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 44898
telemt_me_writer_restored_same_endpoint_total 43709
telemt_me_writer_removed_unexpected_minus_restored_total 1189
telemt_user_connections_total{user="hello"} 114085
telemt_user_connections_current{user="hello"} 380
telemt_user_octets_from_client{user="hello"} 1210345260 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 45550354708 (42.42 GB)
telemt_user_unique_ips_current{user="hello"} 42
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 36327.5 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 326785
telemt_connections_bad_total 102793
telemt_handshake_timeouts_total 9731
telemt_upstream_connect_attempt_total 53043
telemt_upstream_connect_success_total 52721
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 52720
telemt_upstream_connect_attempts_per_request{bucket="2"} 153
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22244
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 693
telemt_me_reconnect_attempts_total 23399
telemt_me_reconnect_success_total 23338
telemt_me_reader_eof_total 24617
telemt_me_idle_close_by_peer_total 24614
telemt_me_route_drop_no_conn_total 91669
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_single_endpoint_shadow_rotate_total 155
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 503
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 134
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 181
telemt_pool_swap_total 3
telemt_pool_force_close_total 113
telemt_me_writer_removed_unexpected_total 24628
telemt_me_writer_restored_same_endpoint_total 23317
telemt_me_writer_removed_unexpected_minus_restored_total 1311
telemt_user_connections_total{user="hello"} 205263
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 1835821984 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 71331888336 (66.43 GB)
telemt_user_unique_ips_current{user="hello"} 45
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 36326.4 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186687
telemt_connections_bad_total 14803
telemt_handshake_timeouts_total 6920
telemt_upstream_connect_attempt_total 27723
telemt_upstream_connect_success_total 27604
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 27604
telemt_upstream_connect_attempts_per_request{bucket="2"} 58
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10478
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 6044
telemt_me_reconnect_success_total 6031
telemt_me_reader_eof_total 6147
telemt_me_idle_close_by_peer_total 6147
telemt_me_route_drop_no_conn_total 56943
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 153
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 10
telemt_pool_force_close_total 232
telemt_me_writer_removed_unexpected_total 6147
telemt_me_writer_restored_same_endpoint_total 6010
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 146411
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 1482217988 (1.38 GB)
telemt_user_octets_to_client{user="hello"} 52816220356 (49.19 GB)
telemt_user_unique_ips_current{user="hello"} 46
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 36325.4 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 327960
telemt_connections_bad_total 6421
telemt_handshake_timeouts_total 129159
telemt_upstream_connect_attempt_total 50822
telemt_upstream_connect_success_total 50473
telemt_upstream_connect_fail_total 162
telemt_upstream_connect_attempts_per_request{bucket="1"} 50473
telemt_upstream_connect_attempts_per_request{bucket="2"} 162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20159
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 162
telemt_me_keepalive_timeout_total 686
telemt_me_reconnect_attempts_total 23306
telemt_me_reconnect_success_total 23290
telemt_me_reader_eof_total 24528
telemt_me_idle_close_by_peer_total 24527
telemt_me_route_drop_no_conn_total 87651
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 154
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 229
telemt_desync_full_logged_total 75
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 117
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 4
telemt_pool_force_close_total 115
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 24541
telemt_me_writer_restored_same_endpoint_total 23265
telemt_me_writer_removed_unexpected_minus_restored_total 1276
telemt_user_connections_total{user="hello"} 186173
telemt_user_connections_current{user="hello"} 416
telemt_user_octets_from_client{user="hello"} 2433786708 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 41745275328 (38.88 GB)
telemt_user_unique_ips_current{user="hello"} 46
```