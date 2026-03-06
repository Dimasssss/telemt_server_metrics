# Server Metrics 2026-03-06 14:33:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 15073.8 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449105
telemt_connections_bad_total 1897
telemt_handshake_timeouts_total 2471
telemt_upstream_connect_attempt_total 8079
telemt_upstream_connect_success_total 8031
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 8049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3763
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 103
telemt_me_reconnect_attempts_total 1828
telemt_me_reconnect_success_total 1819
telemt_me_reader_eof_total 1913
telemt_me_idle_close_by_peer_total 1913
telemt_me_route_drop_no_conn_total 159777
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2419
telemt_desync_full_logged_total 589
telemt_desync_suppressed_total 1830
telemt_desync_frames_bucket_total{bucket="1_2"} 568
telemt_desync_frames_bucket_total{bucket="3_10"} 816
telemt_desync_frames_bucket_total{bucket="gt_10"} 1035
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1915
telemt_me_writer_restored_same_endpoint_total 1813
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 381413
telemt_user_connections_current{user="hello"} 1314
telemt_user_octets_from_client{user="hello"} 10742948888 (10.01 GB)
telemt_user_octets_to_client{user="hello"} 155010526028 (144.36 GB)
telemt_user_unique_ips_current{user="hello"} 345
telemt_user_unique_ips_recent_window{user="hello"} 202
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 15073.7 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 171343
telemt_connections_bad_total 820
telemt_handshake_timeouts_total 5544
telemt_upstream_connect_attempt_total 6484
telemt_upstream_connect_success_total 6468
telemt_upstream_connect_fail_total 16
telemt_upstream_connect_attempts_per_request{bucket="1"} 6484
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3030
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3438
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16
telemt_me_keepalive_timeout_total 91
telemt_me_reconnect_attempts_total 607
telemt_me_reconnect_success_total 598
telemt_me_reader_eof_total 640
telemt_me_idle_close_by_peer_total 640
telemt_me_route_drop_no_conn_total 85078
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 62
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 616
telemt_desync_full_logged_total 201
telemt_desync_suppressed_total 415
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 283
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 640
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 156823
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 1707061316 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 72415572648 (67.44 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 15073.6 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353420
telemt_connections_bad_total 5208
telemt_handshake_timeouts_total 35800
telemt_upstream_connect_attempt_total 11459
telemt_upstream_connect_success_total 11408
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 11451
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6136
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 153
telemt_me_reconnect_attempts_total 3488
telemt_me_reconnect_success_total 3474
telemt_me_reader_eof_total 3685
telemt_me_idle_close_by_peer_total 3685
telemt_me_route_drop_no_conn_total 168360
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 596
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 425
telemt_desync_frames_bucket_total{bucket="1_2"} 136
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 3687
telemt_me_writer_restored_same_endpoint_total 3469
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 300366
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 3125514428 (2.91 GB)
telemt_user_octets_to_client{user="hello"} 96149431208 (89.55 GB)
telemt_user_unique_ips_current{user="hello"} 204
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 14389.9 (3h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 256479
telemt_connections_bad_total 51460
telemt_handshake_timeouts_total 9046
telemt_upstream_connect_attempt_total 7171
telemt_upstream_connect_success_total 7171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2967
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 1031
telemt_me_reconnect_success_total 1019
telemt_me_reader_eof_total 1035
telemt_me_idle_close_by_peer_total 1035
telemt_me_route_drop_no_conn_total 88676
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 258
telemt_desync_full_logged_total 92
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 96
telemt_desync_frames_bucket_total{bucket="gt_10"} 95
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 1035
telemt_me_writer_restored_same_endpoint_total 1019
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 162664
telemt_user_connections_current{user="hello"} 499
telemt_user_octets_from_client{user="hello"} 1976664964 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 61874549016 (57.63 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 15073.8 (4h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 270954
telemt_connections_bad_total 7893
telemt_handshake_timeouts_total 2574
telemt_upstream_connect_attempt_total 7388
telemt_upstream_connect_success_total 7378
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3375
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 1510
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1579
telemt_me_idle_close_by_peer_total 1578
telemt_me_route_drop_no_conn_total 145583
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 61
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 455
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 298
telemt_desync_frames_bucket_total{bucket="1_2"} 201
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1583
telemt_me_writer_restored_same_endpoint_total 1497
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 247592
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 14271580140 (13.29 GB)
telemt_user_octets_to_client{user="hello"} 140500897888 (130.85 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 113
```