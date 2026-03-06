# Server Metrics 2026-03-06 16:42:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 22806.1 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 681452
telemt_connections_bad_total 10916
telemt_handshake_timeouts_total 3105
telemt_upstream_connect_attempt_total 11134
telemt_upstream_connect_success_total 11066
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 11094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5879
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 41
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 145
telemt_me_reconnect_attempts_total 2051
telemt_me_reconnect_success_total 2035
telemt_me_reader_eof_total 2137
telemt_me_idle_close_by_peer_total 2137
telemt_me_route_drop_no_conn_total 293632
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3478
telemt_desync_full_logged_total 837
telemt_desync_suppressed_total 2641
telemt_desync_frames_bucket_total{bucket="1_2"} 837
telemt_desync_frames_bucket_total{bucket="3_10"} 1203
telemt_desync_frames_bucket_total{bucket="gt_10"} 1438
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2139
telemt_me_writer_restored_same_endpoint_total 2029
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 588148
telemt_user_connections_current{user="hello"} 1018
telemt_user_octets_from_client{user="hello"} 13118465060 (12.22 GB)
telemt_user_octets_to_client{user="hello"} 217639987216 (202.69 GB)
telemt_user_unique_ips_current{user="hello"} 283
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 22806.0 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257685
telemt_connections_bad_total 947
telemt_handshake_timeouts_total 7590
telemt_upstream_connect_attempt_total 10582
telemt_upstream_connect_success_total 10557
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 10582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 140
telemt_me_reconnect_attempts_total 958
telemt_me_reconnect_success_total 938
telemt_me_reader_eof_total 989
telemt_me_idle_close_by_peer_total 989
telemt_me_route_drop_no_conn_total 145129
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 825
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 558
telemt_desync_frames_bucket_total{bucket="1_2"} 150
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 373
telemt_pool_swap_total 6
telemt_pool_force_close_total 239
telemt_me_writer_removed_unexpected_total 990
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 236828
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 2725734492 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 96899409772 (90.24 GB)
telemt_user_unique_ips_current{user="hello"} 134
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 22805.9 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 509282
telemt_connections_bad_total 5428
telemt_handshake_timeouts_total 51569
telemt_upstream_connect_attempt_total 19195
telemt_upstream_connect_success_total 19113
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 19182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 6489
telemt_me_reconnect_success_total 6463
telemt_me_reader_eof_total 6844
telemt_me_idle_close_by_peer_total 6844
telemt_me_route_drop_no_conn_total 261015
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 94
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1102
telemt_desync_full_logged_total 331
telemt_desync_suppressed_total 771
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 416
telemt_desync_frames_bucket_total{bucket="gt_10"} 427
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 6856
telemt_me_writer_restored_same_endpoint_total 6456
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 436134
telemt_user_connections_current{user="hello"} 611
telemt_user_octets_from_client{user="hello"} 6306545064 (5.87 GB)
telemt_user_octets_to_client{user="hello"} 134973708056 (125.70 GB)
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 22122.1 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 482248
telemt_connections_bad_total 167239
telemt_handshake_timeouts_total 11750
telemt_upstream_connect_attempt_total 12990
telemt_upstream_connect_success_total 12989
telemt_upstream_connect_attempts_per_request{bucket="1"} 12989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7584
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5405
telemt_me_keepalive_timeout_total 162
telemt_me_reconnect_attempts_total 2915
telemt_me_reconnect_success_total 2896
telemt_me_reader_eof_total 2982
telemt_me_idle_close_by_peer_total 2982
telemt_me_route_drop_no_conn_total 149368
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 95
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 351
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 142
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2988
telemt_me_writer_restored_same_endpoint_total 2895
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 266775
telemt_user_connections_current{user="hello"} 502
telemt_user_octets_from_client{user="hello"} 4620673912 (4.30 GB)
telemt_user_octets_to_client{user="hello"} 93632595688 (87.20 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 22806.4 (6h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 408637
telemt_connections_bad_total 11052
telemt_handshake_timeouts_total 3681
telemt_upstream_connect_attempt_total 10025
telemt_upstream_connect_success_total 10013
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10014
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 1769
telemt_me_reconnect_success_total 1752
telemt_me_reader_eof_total 1847
telemt_me_idle_close_by_peer_total 1846
telemt_me_route_drop_no_conn_total 198838
telemt_me_route_drop_channel_closed_total 5
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 774
telemt_desync_full_logged_total 271
telemt_desync_suppressed_total 503
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 227
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1851
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 375089
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 15512396768 (14.45 GB)
telemt_user_octets_to_client{user="hello"} 193111469164 (179.85 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 87
```