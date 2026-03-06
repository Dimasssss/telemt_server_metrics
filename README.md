# Server Metrics 2026-03-06 14:58:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 16619.7 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 492315
telemt_connections_bad_total 3326
telemt_handshake_timeouts_total 2648
telemt_upstream_connect_attempt_total 8538
telemt_upstream_connect_success_total 8486
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4476
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3956
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 108
telemt_me_reconnect_attempts_total 1835
telemt_me_reconnect_success_total 1825
telemt_me_reader_eof_total 1920
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 175907
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2657
telemt_desync_full_logged_total 653
telemt_desync_suppressed_total 2004
telemt_desync_frames_bucket_total{bucket="1_2"} 632
telemt_desync_frames_bucket_total{bucket="3_10"} 894
telemt_desync_frames_bucket_total{bucket="gt_10"} 1131
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1922
telemt_me_writer_restored_same_endpoint_total 1819
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 421885
telemt_user_connections_current{user="hello"} 1157
telemt_user_octets_from_client{user="hello"} 11313064256 (10.54 GB)
telemt_user_octets_to_client{user="hello"} 169314201880 (157.69 GB)
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 188
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 16617.6 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188328
telemt_connections_bad_total 856
telemt_handshake_timeouts_total 5975
telemt_upstream_connect_attempt_total 7460
telemt_upstream_connect_success_total 7440
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 7460
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3920
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 673
telemt_me_reconnect_success_total 661
telemt_me_reader_eof_total 704
telemt_me_idle_close_by_peer_total 704
telemt_me_route_drop_no_conn_total 94392
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 682
telemt_desync_full_logged_total 217
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 112
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 310
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 704
telemt_me_writer_restored_same_endpoint_total 661
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 173030
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 1949357976 (1.82 GB)
telemt_user_octets_to_client{user="hello"} 76808100788 (71.53 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 16617.5 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380895
telemt_connections_bad_total 5252
telemt_handshake_timeouts_total 36713
telemt_upstream_connect_attempt_total 14137
telemt_upstream_connect_success_total 14073
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 14126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 4803
telemt_me_reconnect_success_total 4785
telemt_me_reader_eof_total 5072
telemt_me_idle_close_by_peer_total 5072
telemt_me_route_drop_no_conn_total 182964
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 686
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 475
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5076
telemt_me_writer_restored_same_endpoint_total 4780
telemt_me_writer_removed_unexpected_minus_restored_total 296
telemt_user_connections_total{user="hello"} 326309
telemt_user_connections_current{user="hello"} 598
telemt_user_octets_from_client{user="hello"} 3469410852 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 103731842148 (96.61 GB)
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 15933.8 (4h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 283373
telemt_connections_bad_total 57899
telemt_handshake_timeouts_total 10014
telemt_upstream_connect_attempt_total 8743
telemt_upstream_connect_success_total 8743
telemt_upstream_connect_attempts_per_request{bucket="1"} 8743
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3488
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 1721
telemt_me_reconnect_success_total 1708
telemt_me_reader_eof_total 1736
telemt_me_idle_close_by_peer_total 1736
telemt_me_route_drop_no_conn_total 96359
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 271
telemt_desync_full_logged_total 94
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 67
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 1736
telemt_me_writer_restored_same_endpoint_total 1708
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 181816
telemt_user_connections_current{user="hello"} 551
telemt_user_octets_from_client{user="hello"} 2180127832 (2.03 GB)
telemt_user_octets_to_client{user="hello"} 68356200592 (63.66 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 16617.7 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297277
telemt_connections_bad_total 9206
telemt_handshake_timeouts_total 2667
telemt_upstream_connect_attempt_total 8077
telemt_upstream_connect_success_total 8065
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3713
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 1656
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 156483
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 524
telemt_desync_full_logged_total 186
telemt_desync_suppressed_total 338
telemt_desync_frames_bucket_total{bucket="1_2"} 237
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 140
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1754
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 271957
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 14534912048 (13.54 GB)
telemt_user_octets_to_client{user="hello"} 150720555280 (140.37 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 112
```