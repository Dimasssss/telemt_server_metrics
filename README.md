# Server Metrics 2026-03-06 15:50:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 19726.8 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 593066
telemt_connections_bad_total 6398
telemt_handshake_timeouts_total 2935
telemt_upstream_connect_attempt_total 9798
telemt_upstream_connect_success_total 9739
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 9763
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5142
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 132
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 1957
telemt_me_reader_eof_total 2055
telemt_me_idle_close_by_peer_total 2055
telemt_me_route_drop_no_conn_total 231460
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 77
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3133
telemt_desync_full_logged_total 759
telemt_desync_suppressed_total 2374
telemt_desync_frames_bucket_total{bucket="1_2"} 746
telemt_desync_frames_bucket_total{bucket="3_10"} 1074
telemt_desync_frames_bucket_total{bucket="gt_10"} 1313
telemt_pool_swap_total 4
telemt_pool_force_close_total 233
telemt_me_writer_removed_unexpected_total 2057
telemt_me_writer_restored_same_endpoint_total 1951
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 506432
telemt_user_connections_current{user="hello"} 1067
telemt_user_octets_from_client{user="hello"} 12188268356 (11.35 GB)
telemt_user_octets_to_client{user="hello"} 193127550736 (179.86 GB)
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 19726.7 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 221981
telemt_connections_bad_total 863
telemt_handshake_timeouts_total 6676
telemt_upstream_connect_attempt_total 9179
telemt_upstream_connect_success_total 9158
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 9179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4391
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 918
telemt_me_reconnect_success_total 902
telemt_me_reader_eof_total 952
telemt_me_idle_close_by_peer_total 952
telemt_me_route_drop_no_conn_total 111639
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 80
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 778
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 138
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 352
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 952
telemt_me_writer_restored_same_endpoint_total 902
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 205065
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 2349788472 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 84735910780 (78.92 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 63
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 19726.6 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443447
telemt_connections_bad_total 5359
telemt_handshake_timeouts_total 40839
telemt_upstream_connect_attempt_total 16129
telemt_upstream_connect_success_total 16054
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 16117
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7202
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 5371
telemt_me_reconnect_success_total 5349
telemt_me_reader_eof_total 5664
telemt_me_idle_close_by_peer_total 5664
telemt_me_route_drop_no_conn_total 213169
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 78
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 899
telemt_desync_full_logged_total 265
telemt_desync_suppressed_total 634
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 339
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5668
telemt_me_writer_restored_same_endpoint_total 5344
telemt_me_writer_removed_unexpected_minus_restored_total 324
telemt_user_connections_total{user="hello"} 383281
telemt_user_connections_current{user="hello"} 655
telemt_user_octets_from_client{user="hello"} 5747693112 (5.35 GB)
telemt_user_octets_to_client{user="hello"} 122098611128 (113.71 GB)
telemt_user_unique_ips_current{user="hello"} 197
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 19042.5 (5h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363071
telemt_connections_bad_total 95363
telemt_handshake_timeouts_total 10403
telemt_upstream_connect_attempt_total 10132
telemt_upstream_connect_success_total 10130
telemt_upstream_connect_attempts_per_request{bucket="1"} 10130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4072
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 1953
telemt_me_reconnect_success_total 1937
telemt_me_reader_eof_total 1976
telemt_me_idle_close_by_peer_total 1976
telemt_me_route_drop_no_conn_total 114743
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 83
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 301
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 193
telemt_desync_frames_bucket_total{bucket="1_2"} 79
telemt_desync_frames_bucket_total{bucket="3_10"} 104
telemt_desync_frames_bucket_total{bucket="gt_10"} 118
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 1976
telemt_me_writer_restored_same_endpoint_total 1937
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 222437
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 2595287848 (2.42 GB)
telemt_user_octets_to_client{user="hello"} 80538655452 (75.01 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 19726.8 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 347143
telemt_connections_bad_total 10808
telemt_handshake_timeouts_total 2794
telemt_upstream_connect_attempt_total 9434
telemt_upstream_connect_success_total 9422
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5102
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4261
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 155
telemt_me_reconnect_attempts_total 1764
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1844
telemt_me_idle_close_by_peer_total 1843
telemt_me_route_drop_no_conn_total 177559
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 76
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 632
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 408
telemt_desync_frames_bucket_total{bucket="1_2"} 287
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 5
telemt_pool_force_close_total 221
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1848
telemt_me_writer_restored_same_endpoint_total 1746
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 318736
telemt_user_connections_current{user="hello"} 527
telemt_user_octets_from_client{user="hello"} 14988599580 (13.96 GB)
telemt_user_octets_to_client{user="hello"} 170488963500 (158.78 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 88
```