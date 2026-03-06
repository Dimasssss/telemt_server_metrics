# Server Metrics 2026-03-06 17:18:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 24966.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 744850
telemt_connections_bad_total 12521
telemt_handshake_timeouts_total 3249
telemt_upstream_connect_attempt_total 12771
telemt_upstream_connect_success_total 12695
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 12727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6828
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 45
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 167
telemt_me_reconnect_attempts_total 2527
telemt_me_reconnect_success_total 2509
telemt_me_reader_eof_total 2621
telemt_me_idle_close_by_peer_total 2621
telemt_me_route_drop_no_conn_total 315977
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3829
telemt_desync_full_logged_total 927
telemt_desync_suppressed_total 2902
telemt_desync_frames_bucket_total{bucket="1_2"} 903
telemt_desync_frames_bucket_total{bucket="3_10"} 1343
telemt_desync_frames_bucket_total{bucket="gt_10"} 1583
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2624
telemt_me_writer_restored_same_endpoint_total 2503
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 638643
telemt_user_connections_current{user="hello"} 1002
telemt_user_octets_from_client{user="hello"} 13540520896 (12.61 GB)
telemt_user_octets_to_client{user="hello"} 231694878012 (215.78 GB)
telemt_user_unique_ips_current{user="hello"} 277
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 24966.1 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277171
telemt_connections_bad_total 975
telemt_handshake_timeouts_total 8223
telemt_upstream_connect_attempt_total 11287
telemt_upstream_connect_success_total 11255
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 11287
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5377
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 148
telemt_me_reconnect_attempts_total 966
telemt_me_reconnect_success_total 943
telemt_me_reader_eof_total 995
telemt_me_idle_close_by_peer_total 995
telemt_me_route_drop_no_conn_total 152349
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 101
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 883
telemt_desync_full_logged_total 280
telemt_desync_suppressed_total 603
telemt_desync_frames_bucket_total{bucket="1_2"} 165
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 996
telemt_me_writer_restored_same_endpoint_total 943
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 255127
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 3077618596 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 102891276780 (95.82 GB)
telemt_user_unique_ips_current{user="hello"} 120
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 24966.0 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 544402
telemt_connections_bad_total 5540
telemt_handshake_timeouts_total 52364
telemt_upstream_connect_attempt_total 22202
telemt_upstream_connect_success_total 22094
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 22171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9878
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 49
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 7761
telemt_me_reconnect_success_total 7732
telemt_me_reader_eof_total 8222
telemt_me_idle_close_by_peer_total 8222
telemt_me_route_drop_no_conn_total 287988
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1311
telemt_desync_full_logged_total 389
telemt_desync_suppressed_total 922
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 493
telemt_desync_frames_bucket_total{bucket="gt_10"} 522
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8237
telemt_me_writer_restored_same_endpoint_total 7725
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 510
telemt_user_connections_total{user="hello"} 468309
telemt_user_connections_current{user="hello"} 650
telemt_user_octets_from_client{user="hello"} 7045385260 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 145276230768 (135.30 GB)
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 24282.2 (6h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 523356
telemt_connections_bad_total 178324
telemt_handshake_timeouts_total 13329
telemt_upstream_connect_attempt_total 16135
telemt_upstream_connect_success_total 16133
telemt_upstream_connect_attempts_per_request{bucket="1"} 16133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6982
telemt_me_keepalive_timeout_total 219
telemt_me_reconnect_attempts_total 4341
telemt_me_reconnect_success_total 4318
telemt_me_reader_eof_total 4520
telemt_me_idle_close_by_peer_total 4520
telemt_me_route_drop_no_conn_total 168968
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 103
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 91
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 4527
telemt_me_writer_restored_same_endpoint_total 4317
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 209
telemt_user_connections_total{user="hello"} 294546
telemt_user_connections_current{user="hello"} 524
telemt_user_octets_from_client{user="hello"} 4941736700 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 101795285256 (94.80 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 24966.4 (6h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454700
telemt_connections_bad_total 11135
telemt_handshake_timeouts_total 4352
telemt_upstream_connect_attempt_total 10755
telemt_upstream_connect_success_total 10738
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4859
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 178
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 1767
telemt_me_reader_eof_total 1867
telemt_me_idle_close_by_peer_total 1866
telemt_me_route_drop_no_conn_total 219478
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 873
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 255
telemt_desync_frames_bucket_total{bucket="gt_10"} 228
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 245
telemt_me_writer_removed_unexpected_total 1871
telemt_me_writer_restored_same_endpoint_total 1764
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 417666
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 20152369052 (18.77 GB)
telemt_user_octets_to_client{user="hello"} 206776952388 (192.58 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 82
```