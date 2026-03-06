# Server Metrics 2026-03-06 17:02:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 24038.6 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 719237
telemt_connections_bad_total 11246
telemt_handshake_timeouts_total 3181
telemt_upstream_connect_attempt_total 12023
telemt_upstream_connect_success_total 11950
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 11980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6406
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5475
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 43
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 2270
telemt_me_reconnect_success_total 2254
telemt_me_reader_eof_total 2360
telemt_me_idle_close_by_peer_total 2360
telemt_me_route_drop_no_conn_total 307855
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 96
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3623
telemt_desync_full_logged_total 874
telemt_desync_suppressed_total 2749
telemt_desync_frames_bucket_total{bucket="1_2"} 871
telemt_desync_frames_bucket_total{bucket="3_10"} 1258
telemt_desync_frames_bucket_total{bucket="gt_10"} 1494
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_restored_same_endpoint_total 2248
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 616924
telemt_user_connections_current{user="hello"} 1164
telemt_user_octets_from_client{user="hello"} 13343592996 (12.43 GB)
telemt_user_octets_to_client{user="hello"} 224842499072 (209.40 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 24038.4 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269522
telemt_connections_bad_total 968
telemt_handshake_timeouts_total 8034
telemt_upstream_connect_attempt_total 11044
telemt_upstream_connect_success_total 11014
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 11044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5277
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5736
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 144
telemt_me_reconnect_attempts_total 964
telemt_me_reconnect_success_total 942
telemt_me_reader_eof_total 994
telemt_me_idle_close_by_peer_total 994
telemt_me_route_drop_no_conn_total 149782
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 854
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 152
telemt_desync_frames_bucket_total{bucket="3_10"} 309
telemt_desync_frames_bucket_total{bucket="gt_10"} 393
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 995
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 247809
telemt_user_connections_current{user="hello"} 475
telemt_user_octets_from_client{user="hello"} 2906452484 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 100397922768 (93.50 GB)
telemt_user_unique_ips_current{user="hello"} 125
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 24038.3 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 530330
telemt_connections_bad_total 5499
telemt_handshake_timeouts_total 52095
telemt_upstream_connect_attempt_total 20815
telemt_upstream_connect_success_total 20714
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 20786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9251
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 304
telemt_me_reconnect_attempts_total 7120
telemt_me_reconnect_success_total 7092
telemt_me_reader_eof_total 7531
telemt_me_idle_close_by_peer_total 7531
telemt_me_route_drop_no_conn_total 277446
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 98
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1248
telemt_desync_full_logged_total 370
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 487
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 7546
telemt_me_writer_restored_same_endpoint_total 7085
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 459
telemt_user_connections_total{user="hello"} 455001
telemt_user_connections_current{user="hello"} 625
telemt_user_octets_from_client{user="hello"} 6494794340 (6.05 GB)
telemt_user_octets_to_client{user="hello"} 139730714852 (130.13 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 23354.5 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505672
telemt_connections_bad_total 173114
telemt_handshake_timeouts_total 12724
telemt_upstream_connect_attempt_total 14716
telemt_upstream_connect_success_total 14714
telemt_upstream_connect_attempts_per_request{bucket="1"} 14714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8424
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6290
telemt_me_keepalive_timeout_total 191
telemt_me_reconnect_attempts_total 3693
telemt_me_reconnect_success_total 3672
telemt_me_reader_eof_total 3827
telemt_me_idle_close_by_peer_total 3827
telemt_me_route_drop_no_conn_total 160648
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 99
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 355
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 222
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 3833
telemt_me_writer_restored_same_endpoint_total 3671
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 161
telemt_user_connections_total{user="hello"} 282856
telemt_user_connections_current{user="hello"} 541
telemt_user_octets_from_client{user="hello"} 4813202860 (4.48 GB)
telemt_user_octets_to_client{user="hello"} 98149106360 (91.41 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 24038.6 (6h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431146
telemt_connections_bad_total 11056
telemt_handshake_timeouts_total 3895
telemt_upstream_connect_attempt_total 10564
telemt_upstream_connect_success_total 10547
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10548
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5714
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4768
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 64
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 1778
telemt_me_reconnect_success_total 1759
telemt_me_reader_eof_total 1858
telemt_me_idle_close_by_peer_total 1857
telemt_me_route_drop_no_conn_total 212500
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 845
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 548
telemt_desync_frames_bucket_total{bucket="1_2"} 375
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 223
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1862
telemt_me_writer_restored_same_endpoint_total 1756
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 396132
telemt_user_connections_current{user="hello"} 562
telemt_user_octets_from_client{user="hello"} 19986088724 (18.61 GB)
telemt_user_octets_to_client{user="hello"} 200560062292 (186.79 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 89
```