# Server Metrics 2026-03-06 12:40:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 8291.4 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262771
telemt_connections_bad_total 1623
telemt_handshake_timeouts_total 1457
telemt_upstream_connect_attempt_total 2767
telemt_upstream_connect_success_total 2740
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2752
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 113
telemt_me_reconnect_success_total 110
telemt_me_reader_eof_total 113
telemt_me_idle_close_by_peer_total 113
telemt_me_route_drop_no_conn_total 76265
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1295
telemt_desync_full_logged_total 311
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 318
telemt_desync_frames_bucket_total{bucket="3_10"} 468
telemt_desync_frames_bucket_total{bucket="gt_10"} 509
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 113
telemt_me_writer_restored_same_endpoint_total 104
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 203511
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 4120881764 (3.84 GB)
telemt_user_octets_to_client{user="hello"} 85317294708 (79.46 GB)
telemt_user_unique_ips_current{user="hello"} 296
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 8291.2 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93923
telemt_connections_bad_total 751
telemt_handshake_timeouts_total 3562
telemt_upstream_connect_attempt_total 3889
telemt_upstream_connect_success_total 3879
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 3889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2120
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 525
telemt_me_reconnect_success_total 522
telemt_me_reader_eof_total 558
telemt_me_idle_close_by_peer_total 558
telemt_me_route_drop_no_conn_total 35244
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 296
telemt_desync_full_logged_total 106
telemt_desync_suppressed_total 190
telemt_desync_frames_bucket_total{bucket="1_2"} 54
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 3
telemt_pool_force_close_total 76
telemt_me_writer_removed_unexpected_total 558
telemt_me_writer_restored_same_endpoint_total 522
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 83852
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 886170576 (845.12 MB)
telemt_user_octets_to_client{user="hello"} 38972531416 (36.30 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 8295.9 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183118
telemt_connections_bad_total 2182
telemt_handshake_timeouts_total 13428
telemt_upstream_connect_attempt_total 5221
telemt_upstream_connect_success_total 5194
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5217
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2264
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 1452
telemt_me_reconnect_success_total 1448
telemt_me_reader_eof_total 1518
telemt_me_idle_close_by_peer_total 1518
telemt_me_route_drop_no_conn_total 81565
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 254
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 182
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 103
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 269
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_restored_same_endpoint_total 1443
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 161605
telemt_user_connections_current{user="hello"} 797
telemt_user_octets_from_client{user="hello"} 1742035956 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 53665021804 (49.98 GB)
telemt_user_unique_ips_current{user="hello"} 212
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 7607.1 (2h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96674
telemt_connections_bad_total 16098
telemt_handshake_timeouts_total 2167
telemt_upstream_connect_attempt_total 4052
telemt_upstream_connect_success_total 4052
telemt_upstream_connect_attempts_per_request{bucket="1"} 4052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1723
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 565
telemt_me_reconnect_success_total 560
telemt_me_reader_eof_total 568
telemt_me_idle_close_by_peer_total 568
telemt_me_route_drop_no_conn_total 33417
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 119
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 74
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 35
telemt_desync_frames_bucket_total{bucket="gt_10"} 57
telemt_pool_swap_total 1
telemt_pool_force_close_total 37
telemt_me_writer_removed_unexpected_total 568
telemt_me_writer_restored_same_endpoint_total 560
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 76834
telemt_user_connections_current{user="hello"} 466
telemt_user_octets_from_client{user="hello"} 952580140 (908.45 MB)
telemt_user_octets_to_client{user="hello"} 32897102352 (30.64 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 8291.3 (2h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 157948
telemt_connections_bad_total 3296
telemt_handshake_timeouts_total 2214
telemt_upstream_connect_attempt_total 2559
telemt_upstream_connect_success_total 2554
telemt_upstream_connect_attempts_per_request{bucket="1"} 2554
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1217
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 102
telemt_me_reconnect_success_total 95
telemt_me_reader_eof_total 98
telemt_me_idle_close_by_peer_total 98
telemt_me_route_drop_no_conn_total 74098
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 250
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 166
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 87
telemt_desync_frames_bucket_total{bucket="gt_10"} 85
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 99
telemt_me_writer_restored_same_endpoint_total 95
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 142266
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 13407364756 (12.49 GB)
telemt_user_octets_to_client{user="hello"} 81760320268 (76.15 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 138
```