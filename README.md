# Server Metrics 2026-03-06 16:11:14 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 20956.9 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 633791
telemt_connections_bad_total 8834
telemt_handshake_timeouts_total 3005
telemt_upstream_connect_attempt_total 10229
telemt_upstream_connect_success_total 10167
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 10194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 135
telemt_me_reconnect_attempts_total 1989
telemt_me_reconnect_success_total 1975
telemt_me_reader_eof_total 2075
telemt_me_idle_close_by_peer_total 2075
telemt_me_route_drop_no_conn_total 265444
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 85
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3265
telemt_desync_full_logged_total 789
telemt_desync_suppressed_total 2476
telemt_desync_frames_bucket_total{bucket="1_2"} 778
telemt_desync_frames_bucket_total{bucket="3_10"} 1122
telemt_desync_frames_bucket_total{bucket="gt_10"} 1365
telemt_pool_swap_total 4
telemt_pool_force_close_total 234
telemt_me_writer_removed_unexpected_total 2077
telemt_me_writer_restored_same_endpoint_total 1969
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 543842
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 12533006548 (11.67 GB)
telemt_user_octets_to_client{user="hello"} 204147404060 (190.13 GB)
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 20956.7 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236274
telemt_connections_bad_total 866
telemt_handshake_timeouts_total 6863
telemt_upstream_connect_attempt_total 9883
telemt_upstream_connect_success_total 9860
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 9883
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5099
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 125
telemt_me_reconnect_attempts_total 942
telemt_me_reconnect_success_total 924
telemt_me_reader_eof_total 975
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 131881
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_single_endpoint_shadow_rotate_total 88
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 798
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 537
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 358
telemt_pool_swap_total 5
telemt_pool_force_close_total 196
telemt_me_writer_removed_unexpected_total 976
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 218696
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 2448865432 (2.28 GB)
telemt_user_octets_to_client{user="hello"} 88326253612 (82.26 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 20956.5 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477787
telemt_connections_bad_total 5385
telemt_handshake_timeouts_total 48817
telemt_upstream_connect_attempt_total 17023
telemt_upstream_connect_success_total 16944
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 17011
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9411
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7501
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_timeout_total 228
telemt_me_reconnect_attempts_total 5572
telemt_me_reconnect_success_total 5548
telemt_me_reader_eof_total 5861
telemt_me_idle_close_by_peer_total 5861
telemt_me_route_drop_no_conn_total 238404
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 86
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 991
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 378
telemt_desync_frames_bucket_total{bucket="gt_10"} 382
telemt_pool_swap_total 2
telemt_pool_force_close_total 169
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 5873
telemt_me_writer_restored_same_endpoint_total 5541
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 408210
telemt_user_connections_current{user="hello"} 646
telemt_user_octets_from_client{user="hello"} 6028236208 (5.61 GB)
telemt_user_octets_to_client{user="hello"} 128919494052 (120.07 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 20272.8 (5h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 417705
telemt_connections_bad_total 131339
telemt_handshake_timeouts_total 10693
telemt_upstream_connect_attempt_total 10908
telemt_upstream_connect_success_total 10907
telemt_upstream_connect_attempts_per_request{bucket="1"} 10907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6508
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4399
telemt_me_keepalive_timeout_total 131
telemt_me_reconnect_attempts_total 2085
telemt_me_reconnect_success_total 2068
telemt_me_reader_eof_total 2107
telemt_me_idle_close_by_peer_total 2107
telemt_me_route_drop_no_conn_total 128954
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 87
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 336
telemt_desync_full_logged_total 124
telemt_desync_suppressed_total 212
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 139
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 2113
telemt_me_writer_restored_same_endpoint_total 2067
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 240194
telemt_user_connections_current{user="hello"} 640
telemt_user_octets_from_client{user="hello"} 3653662720 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 87631449772 (81.61 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 20956.9 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369910
telemt_connections_bad_total 11042
telemt_handshake_timeouts_total 2943
telemt_upstream_connect_attempt_total 9677
telemt_upstream_connect_success_total 9665
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5258
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 159
telemt_me_reconnect_attempts_total 1766
telemt_me_reconnect_success_total 1750
telemt_me_reader_eof_total 1845
telemt_me_idle_close_by_peer_total 1844
telemt_me_route_drop_no_conn_total 186648
telemt_me_route_drop_channel_closed_total 4
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 82
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 680
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 442
telemt_desync_frames_bucket_total{bucket="1_2"} 313
telemt_desync_frames_bucket_total{bucket="3_10"} 201
telemt_desync_frames_bucket_total{bucket="gt_10"} 166
telemt_pool_swap_total 7
telemt_pool_force_close_total 255
telemt_pool_stale_pick_total 160
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_restored_same_endpoint_total 1747
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 339655
telemt_user_connections_current{user="hello"} 573
telemt_user_octets_from_client{user="hello"} 15163083336 (14.12 GB)
telemt_user_octets_to_client{user="hello"} 178118681168 (165.89 GB)
telemt_user_unique_ips_current{user="hello"} 162
telemt_user_unique_ips_recent_window{user="hello"} 107
```