# Server Metrics 2026-03-06 13:26:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 11070.6 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 337958
telemt_connections_bad_total 1660
telemt_handshake_timeouts_total 1801
telemt_upstream_connect_attempt_total 4433
telemt_upstream_connect_success_total 4401
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 4415
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1886
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 17
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 405
telemt_me_reconnect_success_total 399
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 105385
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1808
telemt_desync_full_logged_total 437
telemt_desync_suppressed_total 1371
telemt_desync_frames_bucket_total{bucket="1_2"} 417
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 766
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 274120
telemt_user_connections_current{user="hello"} 1125
telemt_user_octets_from_client{user="hello"} 5224568764 (4.87 GB)
telemt_user_octets_to_client{user="hello"} 116327953588 (108.34 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 11070.3 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 125776
telemt_connections_bad_total 807
telemt_handshake_timeouts_total 4110
telemt_upstream_connect_attempt_total 4763
telemt_upstream_connect_success_total 4748
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 4763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2576
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 69
telemt_me_reconnect_attempts_total 540
telemt_me_reconnect_success_total 535
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 51512
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 376
telemt_desync_full_logged_total 132
telemt_desync_suppressed_total 244
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 140
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_restored_same_endpoint_total 535
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 113772
telemt_user_connections_current{user="hello"} 449
telemt_user_octets_from_client{user="hello"} 1181524204 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 53105961428 (49.46 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 11070.1 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262243
telemt_connections_bad_total 4150
telemt_handshake_timeouts_total 21799
telemt_upstream_connect_attempt_total 6369
telemt_upstream_connect_success_total 6332
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 6362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2886
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 1515
telemt_me_reconnect_success_total 1509
telemt_me_reader_eof_total 1582
telemt_me_idle_close_by_peer_total 1582
telemt_me_route_drop_no_conn_total 122609
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 46
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 401
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 288
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1583
telemt_me_writer_restored_same_endpoint_total 1504
telemt_me_writer_removed_unexpected_minus_restored_total 79
telemt_user_connections_total{user="hello"} 227367
telemt_user_connections_current{user="hello"} 645
telemt_user_octets_from_client{user="hello"} 2287694956 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 74279430856 (69.18 GB)
telemt_user_unique_ips_current{user="hello"} 180
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 10386.3 (2h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148437
telemt_connections_bad_total 32874
telemt_handshake_timeouts_total 2893
telemt_upstream_connect_attempt_total 5306
telemt_upstream_connect_success_total 5306
telemt_upstream_connect_attempts_per_request{bucket="1"} 5306
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2256
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 750
telemt_me_reconnect_success_total 743
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 60814
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 192
telemt_desync_full_logged_total 71
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 55
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 755
telemt_me_writer_restored_same_endpoint_total 743
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 110474
telemt_user_connections_current{user="hello"} 550
telemt_user_octets_from_client{user="hello"} 1354196976 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 45444298772 (42.32 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 11070.5 (3h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206096
telemt_connections_bad_total 7573
telemt_handshake_timeouts_total 2392
telemt_upstream_connect_attempt_total 3644
telemt_upstream_connect_success_total 3638
telemt_upstream_connect_attempts_per_request{bucket="1"} 3638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1647
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 195
telemt_me_reconnect_success_total 188
telemt_me_reader_eof_total 194
telemt_me_idle_close_by_peer_total 194
telemt_me_route_drop_no_conn_total 105728
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 315
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 97
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 195
telemt_me_writer_restored_same_endpoint_total 187
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 184824
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 13793211588 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 106163586284 (98.87 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 75
```