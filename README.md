# Server Metrics 2026-03-06 15:04:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 16927.4 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501264
telemt_connections_bad_total 3618
telemt_handshake_timeouts_total 2675
telemt_upstream_connect_attempt_total 8641
telemt_upstream_connect_success_total 8589
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 8611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4523
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4012
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 112
telemt_me_reconnect_attempts_total 1835
telemt_me_reconnect_success_total 1825
telemt_me_reader_eof_total 1920
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 180364
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 2696
telemt_desync_full_logged_total 662
telemt_desync_suppressed_total 2034
telemt_desync_frames_bucket_total{bucket="1_2"} 641
telemt_desync_frames_bucket_total{bucket="3_10"} 906
telemt_desync_frames_bucket_total{bucket="gt_10"} 1149
telemt_pool_swap_total 3
telemt_pool_force_close_total 177
telemt_me_writer_removed_unexpected_total 1922
telemt_me_writer_restored_same_endpoint_total 1819
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 430310
telemt_user_connections_current{user="hello"} 1096
telemt_user_octets_from_client{user="hello"} 11379144996 (10.60 GB)
telemt_user_octets_to_client{user="hello"} 172052163344 (160.24 GB)
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 197
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 16927.2 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192216
telemt_connections_bad_total 857
telemt_handshake_timeouts_total 6030
telemt_upstream_connect_attempt_total 7707
telemt_upstream_connect_success_total 7687
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 7707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 709
telemt_me_reconnect_success_total 697
telemt_me_reader_eof_total 740
telemt_me_idle_close_by_peer_total 740
telemt_me_route_drop_no_conn_total 96519
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 686
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 260
telemt_desync_frames_bucket_total{bucket="gt_10"} 313
telemt_pool_swap_total 4
telemt_pool_force_close_total 140
telemt_me_writer_removed_unexpected_total 740
telemt_me_writer_restored_same_endpoint_total 697
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 176749
telemt_user_connections_current{user="hello"} 477
telemt_user_octets_from_client{user="hello"} 1971874560 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 78104656028 (72.74 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 16927.2 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 387734
telemt_connections_bad_total 5263
telemt_handshake_timeouts_total 37068
telemt_upstream_connect_attempt_total 14695
telemt_upstream_connect_success_total 14630
telemt_upstream_connect_fail_total 53
telemt_upstream_connect_attempts_per_request{bucket="1"} 14683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7976
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6628
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 53
telemt_me_keepalive_timeout_total 200
telemt_me_reconnect_attempts_total 5098
telemt_me_reconnect_success_total 5079
telemt_me_reader_eof_total 5387
telemt_me_idle_close_by_peer_total 5387
telemt_me_route_drop_no_conn_total 186584
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 69
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 707
telemt_desync_full_logged_total 216
telemt_desync_suppressed_total 491
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 287
telemt_desync_frames_bucket_total{bucket="gt_10"} 258
telemt_pool_swap_total 1
telemt_pool_force_close_total 84
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5391
telemt_me_writer_restored_same_endpoint_total 5074
telemt_me_writer_removed_unexpected_minus_restored_total 317
telemt_user_connections_total{user="hello"} 332710
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 3532462852 (3.29 GB)
telemt_user_octets_to_client{user="hello"} 105697971376 (98.44 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 16243.2 (4h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 287981
telemt_connections_bad_total 58181
telemt_handshake_timeouts_total 10072
telemt_upstream_connect_attempt_total 9140
telemt_upstream_connect_success_total 9140
telemt_upstream_connect_attempts_per_request{bucket="1"} 9140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5519
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3621
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 1903
telemt_me_reconnect_success_total 1890
telemt_me_reader_eof_total 1924
telemt_me_idle_close_by_peer_total 1924
telemt_me_route_drop_no_conn_total 98374
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 275
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 179
telemt_desync_frames_bucket_total{bucket="1_2"} 71
telemt_desync_frames_bucket_total{bucket="3_10"} 100
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 3
telemt_pool_force_close_total 135
telemt_me_writer_removed_unexpected_total 1924
telemt_me_writer_restored_same_endpoint_total 1890
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 185981
telemt_user_connections_current{user="hello"} 532
telemt_user_octets_from_client{user="hello"} 2235533660 (2.08 GB)
telemt_user_octets_to_client{user="hello"} 69999184300 (65.19 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 16934.6 (4h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303400
telemt_connections_bad_total 9371
telemt_handshake_timeouts_total 2673
telemt_upstream_connect_attempt_total 8170
telemt_upstream_connect_success_total 8158
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8159
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4360
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3751
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 133
telemt_me_reconnect_attempts_total 1670
telemt_me_reconnect_success_total 1656
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 159158
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 66
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 529
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 340
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 147
telemt_desync_frames_bucket_total{bucket="gt_10"} 141
telemt_pool_swap_total 4
telemt_pool_force_close_total 178
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1754
telemt_me_writer_restored_same_endpoint_total 1655
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 277802
telemt_user_connections_current{user="hello"} 653
telemt_user_octets_from_client{user="hello"} 14584978440 (13.58 GB)
telemt_user_octets_to_client{user="hello"} 152696785308 (142.21 GB)
telemt_user_unique_ips_current{user="hello"} 178
telemt_user_unique_ips_recent_window{user="hello"} 123
```