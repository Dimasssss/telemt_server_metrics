# Server Metrics 2026-03-06 14:07:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 13530.8 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 404421
telemt_connections_bad_total 1836
telemt_handshake_timeouts_total 2176
telemt_upstream_connect_attempt_total 6925
telemt_upstream_connect_success_total 6881
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 23
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 1382
telemt_me_reconnect_success_total 1373
telemt_me_reader_eof_total 1443
telemt_me_idle_close_by_peer_total 1443
telemt_me_route_drop_no_conn_total 140248
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2189
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 1663
telemt_desync_frames_bucket_total{bucket="1_2"} 508
telemt_desync_frames_bucket_total{bucket="3_10"} 745
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 1444
telemt_me_writer_restored_same_endpoint_total 1367
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 338319
telemt_user_connections_current{user="hello"} 1248
telemt_user_octets_from_client{user="hello"} 10143225208 (9.45 GB)
telemt_user_octets_to_client{user="hello"} 140158425328 (130.53 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 13530.6 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152652
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 4698
telemt_upstream_connect_attempt_total 5944
telemt_upstream_connect_success_total 5928
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 5944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 85
telemt_me_reconnect_attempts_total 596
telemt_me_reconnect_success_total 588
telemt_me_reader_eof_total 627
telemt_me_idle_close_by_peer_total 627
telemt_me_route_drop_no_conn_total 73118
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 574
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 388
telemt_desync_frames_bucket_total{bucket="1_2"} 88
telemt_desync_frames_bucket_total{bucket="3_10"} 216
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 139370
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 1512402976 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 65937362044 (61.41 GB)
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 13530.4 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323992
telemt_connections_bad_total 5086
telemt_handshake_timeouts_total 34916
telemt_upstream_connect_attempt_total 9093
telemt_upstream_connect_success_total 9050
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 9086
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4867
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 2441
telemt_me_reconnect_success_total 2431
telemt_me_reader_eof_total 2566
telemt_me_idle_close_by_peer_total 2566
telemt_me_route_drop_no_conn_total 151316
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 549
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 126
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 2567
telemt_me_writer_restored_same_endpoint_total 2426
telemt_me_writer_removed_unexpected_minus_restored_total 141
telemt_user_connections_total{user="hello"} 272447
telemt_user_connections_current{user="hello"} 632
telemt_user_octets_from_client{user="hello"} 2883439036 (2.69 GB)
telemt_user_octets_to_client{user="hello"} 87377177724 (81.38 GB)
telemt_user_unique_ips_current{user="hello"} 188
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 12846.6 (3h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214533
telemt_connections_bad_total 41590
telemt_handshake_timeouts_total 5536
telemt_upstream_connect_attempt_total 6202
telemt_upstream_connect_success_total 6202
telemt_upstream_connect_attempts_per_request{bucket="1"} 6202
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2589
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 792
telemt_me_reconnect_success_total 782
telemt_me_reader_eof_total 794
telemt_me_idle_close_by_peer_total 794
telemt_me_route_drop_no_conn_total 78668
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 57
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 160
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 794
telemt_me_writer_restored_same_endpoint_total 782
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 143156
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 1698475976 (1.58 GB)
telemt_user_octets_to_client{user="hello"} 56470883404 (52.59 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 13530.6 (3h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 244212
telemt_connections_bad_total 7883
telemt_handshake_timeouts_total 2496
telemt_upstream_connect_attempt_total 5563
telemt_upstream_connect_success_total 5555
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 5556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3093
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2425
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 770
telemt_me_reconnect_success_total 760
telemt_me_reader_eof_total 782
telemt_me_idle_close_by_peer_total 781
telemt_me_route_drop_no_conn_total 126963
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 386
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 251
telemt_desync_frames_bucket_total{bucket="1_2"} 176
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 785
telemt_me_writer_restored_same_endpoint_total 759
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 221611
telemt_user_connections_current{user="hello"} 667
telemt_user_octets_from_client{user="hello"} 14041361368 (13.08 GB)
telemt_user_octets_to_client{user="hello"} 125479657488 (116.86 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 111
```