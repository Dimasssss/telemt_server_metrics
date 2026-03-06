# Server Metrics 2026-03-06 13:05:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 9839.2 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 306492
telemt_connections_bad_total 1656
telemt_handshake_timeouts_total 1639
telemt_upstream_connect_attempt_total 3536
telemt_upstream_connect_success_total 3508
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 3521
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1524
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 13
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 209
telemt_me_reconnect_success_total 204
telemt_me_reader_eof_total 210
telemt_me_idle_close_by_peer_total 210
telemt_me_route_drop_no_conn_total 92626
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1605
telemt_desync_full_logged_total 387
telemt_desync_suppressed_total 1218
telemt_desync_frames_bucket_total{bucket="1_2"} 371
telemt_desync_frames_bucket_total{bucket="3_10"} 563
telemt_desync_frames_bucket_total{bucket="gt_10"} 671
telemt_pool_swap_total 2
telemt_pool_force_close_total 82
telemt_me_writer_removed_unexpected_total 210
telemt_me_writer_restored_same_endpoint_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 243918
telemt_user_connections_current{user="hello"} 1262
telemt_user_octets_from_client{user="hello"} 4635118012 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 102346641720 (95.32 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 9838.9 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 113528
telemt_connections_bad_total 805
telemt_handshake_timeouts_total 3923
telemt_upstream_connect_attempt_total 4171
telemt_upstream_connect_success_total 4161
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 4171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2301
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 64
telemt_me_reconnect_attempts_total 531
telemt_me_reconnect_success_total 526
telemt_me_reader_eof_total 563
telemt_me_idle_close_by_peer_total 563
telemt_me_route_drop_no_conn_total 43871
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 348
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 154
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_restored_same_endpoint_total 526
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 102035
telemt_user_connections_current{user="hello"} 529
telemt_user_octets_from_client{user="hello"} 1063428156 (1014.16 MB)
telemt_user_octets_to_client{user="hello"} 45948153656 (42.79 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 9838.8 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229914
telemt_connections_bad_total 3247
telemt_handshake_timeouts_total 15005
telemt_upstream_connect_attempt_total 5638
telemt_upstream_connect_success_total 5606
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 5631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2539
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 1457
telemt_me_reconnect_success_total 1453
telemt_me_reader_eof_total 1523
telemt_me_idle_close_by_peer_total 1523
telemt_me_route_drop_no_conn_total 106758
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 312
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 76
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 364
telemt_me_writer_removed_unexpected_total 1524
telemt_me_writer_restored_same_endpoint_total 1448
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 203453
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 2070437768 (1.93 GB)
telemt_user_octets_to_client{user="hello"} 63643842260 (59.27 GB)
telemt_user_unique_ips_current{user="hello"} 209
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 9154.9 (2h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127311
telemt_connections_bad_total 27620
telemt_handshake_timeouts_total 2584
telemt_upstream_connect_attempt_total 4762
telemt_upstream_connect_success_total 4762
telemt_upstream_connect_attempts_per_request{bucket="1"} 4762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2032
telemt_me_keepalive_timeout_total 61
telemt_me_reconnect_attempts_total 721
telemt_me_reconnect_success_total 715
telemt_me_reader_eof_total 726
telemt_me_idle_close_by_peer_total 726
telemt_me_route_drop_no_conn_total 48417
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 41
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 179
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 114
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 65
telemt_desync_frames_bucket_total{bucket="gt_10"} 66
telemt_pool_swap_total 2
telemt_pool_force_close_total 96
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_restored_same_endpoint_total 715
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 95301
telemt_user_connections_current{user="hello"} 506
telemt_user_octets_from_client{user="hello"} 1231498240 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 39050553536 (36.37 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 9839.0 (2h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185604
telemt_connections_bad_total 5763
telemt_handshake_timeouts_total 2356
telemt_upstream_connect_attempt_total 2953
telemt_upstream_connect_success_total 2947
telemt_upstream_connect_attempts_per_request{bucket="1"} 2947
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 36
telemt_me_reconnect_attempts_total 113
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 111
telemt_me_idle_close_by_peer_total 111
telemt_me_route_drop_no_conn_total 87530
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 37
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 287
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 107
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 112
telemt_me_writer_restored_same_endpoint_total 105
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 166590
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 13681171464 (12.74 GB)
telemt_user_octets_to_client{user="hello"} 96258436608 (89.65 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 95
```