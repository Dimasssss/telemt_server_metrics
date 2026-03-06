# Server Metrics 2026-03-06 13:46:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 12300.8 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370841
telemt_connections_bad_total 1695
telemt_handshake_timeouts_total 2028
telemt_upstream_connect_attempt_total 5662
telemt_upstream_connect_success_total 5624
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 60
telemt_me_reconnect_attempts_total 898
telemt_me_reconnect_success_total 889
telemt_me_reader_eof_total 943
telemt_me_idle_close_by_peer_total 943
telemt_me_route_drop_no_conn_total 122273
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2005
telemt_desync_full_logged_total 477
telemt_desync_suppressed_total 1528
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 687
telemt_desync_frames_bucket_total{bucket="gt_10"} 857
telemt_pool_swap_total 2
telemt_pool_force_close_total 83
telemt_me_writer_removed_unexpected_total 943
telemt_me_writer_restored_same_endpoint_total 883
telemt_me_writer_removed_unexpected_minus_restored_total 60
telemt_user_connections_total{user="hello"} 305928
telemt_user_connections_current{user="hello"} 1082
telemt_user_octets_from_client{user="hello"} 5848412232 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 128641284840 (119.81 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 12300.7 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 138535
telemt_connections_bad_total 815
telemt_handshake_timeouts_total 4304
telemt_upstream_connect_attempt_total 5590
telemt_upstream_connect_success_total 5575
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2977
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 79
telemt_me_reconnect_attempts_total 578
telemt_me_reconnect_success_total 571
telemt_me_reader_eof_total 609
telemt_me_idle_close_by_peer_total 609
telemt_me_route_drop_no_conn_total 61908
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 473
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 309
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 3
telemt_pool_force_close_total 94
telemt_me_writer_removed_unexpected_total 609
telemt_me_writer_restored_same_endpoint_total 571
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 126033
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 1356944924 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 60128356268 (56.00 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 12300.5 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293610
telemt_connections_bad_total 5036
telemt_handshake_timeouts_total 28250
telemt_upstream_connect_attempt_total 7510
telemt_upstream_connect_success_total 7472
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 7503
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3986
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3471
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 1796
telemt_me_reconnect_success_total 1788
telemt_me_reader_eof_total 1882
telemt_me_idle_close_by_peer_total 1882
telemt_me_route_drop_no_conn_total 138071
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 50
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 473
telemt_desync_full_logged_total 136
telemt_desync_suppressed_total 337
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 203
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 1
telemt_pool_force_close_total 83
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 1883
telemt_me_writer_restored_same_endpoint_total 1783
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 250116
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 2439511956 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 79557518904 (74.09 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 11616.7 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172041
telemt_connections_bad_total 37862
telemt_handshake_timeouts_total 3081
telemt_upstream_connect_attempt_total 5678
telemt_upstream_connect_success_total 5678
telemt_upstream_connect_attempts_per_request{bucket="1"} 5678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2406
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 762
telemt_me_reconnect_success_total 754
telemt_me_reader_eof_total 766
telemt_me_idle_close_by_peer_total 766
telemt_me_route_drop_no_conn_total 68665
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 218
telemt_desync_full_logged_total 79
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 60
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 766
telemt_me_writer_restored_same_endpoint_total 754
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 126315
telemt_user_connections_current{user="hello"} 615
telemt_user_octets_from_client{user="hello"} 1516330268 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 51069237324 (47.56 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 12300.8 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224801
telemt_connections_bad_total 7765
telemt_handshake_timeouts_total 2425
telemt_upstream_connect_attempt_total 4503
telemt_upstream_connect_success_total 4495
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 4496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2517
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1951
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 414
telemt_me_reconnect_success_total 406
telemt_me_reader_eof_total 418
telemt_me_idle_close_by_peer_total 418
telemt_me_route_drop_no_conn_total 116198
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 344
telemt_desync_full_logged_total 119
telemt_desync_suppressed_total 225
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 3
telemt_pool_force_close_total 111
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 419
telemt_me_writer_restored_same_endpoint_total 405
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 202842
telemt_user_connections_current{user="hello"} 500
telemt_user_octets_from_client{user="hello"} 13924278252 (12.97 GB)
telemt_user_octets_to_client{user="hello"} 115670166972 (107.73 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 93
```