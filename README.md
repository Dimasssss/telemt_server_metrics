# Server Metrics 2026-03-06 17:33:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 25895.3 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768922
telemt_connections_bad_total 13378
telemt_handshake_timeouts_total 3325
telemt_upstream_connect_attempt_total 13167
telemt_upstream_connect_success_total 13086
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 13119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5942
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 46
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 174
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 2644
telemt_me_reader_eof_total 2770
telemt_me_idle_close_by_peer_total 2770
telemt_me_route_drop_no_conn_total 324215
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 102
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 3907
telemt_desync_full_logged_total 958
telemt_desync_suppressed_total 2949
telemt_desync_frames_bucket_total{bucket="1_2"} 917
telemt_desync_frames_bucket_total{bucket="3_10"} 1371
telemt_desync_frames_bucket_total{bucket="gt_10"} 1619
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2773
telemt_me_writer_restored_same_endpoint_total 2638
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 661068
telemt_user_connections_current{user="hello"} 1174
telemt_user_octets_from_client{user="hello"} 13802265172 (12.85 GB)
telemt_user_octets_to_client{user="hello"} 246861495996 (229.91 GB)
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 25895.1 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285608
telemt_connections_bad_total 1136
telemt_handshake_timeouts_total 8308
telemt_upstream_connect_attempt_total 11598
telemt_upstream_connect_success_total 11565
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 11598
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6029
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 976
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 1005
telemt_me_idle_close_by_peer_total 1005
telemt_me_route_drop_no_conn_total 154573
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 909
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 620
telemt_desync_frames_bucket_total{bucket="1_2"} 167
telemt_desync_frames_bucket_total{bucket="3_10"} 330
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1006
telemt_me_writer_restored_same_endpoint_total 952
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 263018
telemt_user_connections_current{user="hello"} 461
telemt_user_octets_from_client{user="hello"} 3278371956 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 105303868568 (98.07 GB)
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 25895.0 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 557768
telemt_connections_bad_total 5552
telemt_handshake_timeouts_total 52723
telemt_upstream_connect_attempt_total 22787
telemt_upstream_connect_success_total 22678
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 22757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10142
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 340
telemt_me_reconnect_attempts_total 7964
telemt_me_reconnect_success_total 7934
telemt_me_reader_eof_total 8430
telemt_me_idle_close_by_peer_total 8430
telemt_me_route_drop_no_conn_total 294725
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1422
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 1009
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 531
telemt_desync_frames_bucket_total{bucket="gt_10"} 568
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8445
telemt_me_writer_restored_same_endpoint_total 7927
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 480839
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 7193969928 (6.70 GB)
telemt_user_octets_to_client{user="hello"} 148750467924 (138.53 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 25211.0 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 538705
telemt_connections_bad_total 182153
telemt_handshake_timeouts_total 13838
telemt_upstream_connect_attempt_total 17692
telemt_upstream_connect_success_total 17689
telemt_upstream_connect_attempts_per_request{bucket="1"} 17689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9964
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7725
telemt_me_keepalive_timeout_total 246
telemt_me_reconnect_attempts_total 5085
telemt_me_reconnect_success_total 5060
telemt_me_reader_eof_total 5301
telemt_me_idle_close_by_peer_total 5301
telemt_me_route_drop_no_conn_total 176009
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_single_endpoint_shadow_rotate_total 107
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 368
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 226
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 4
telemt_pool_force_close_total 192
telemt_me_writer_removed_unexpected_total 5307
telemt_me_writer_restored_same_endpoint_total 5059
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 305063
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 5053525956 (4.71 GB)
telemt_user_octets_to_client{user="hello"} 107563709468 (100.18 GB)
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 25895.4 (7h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 480352
telemt_connections_bad_total 11141
telemt_handshake_timeouts_total 4945
telemt_upstream_connect_attempt_total 10923
telemt_upstream_connect_success_total 10906
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10907
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4953
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 180
telemt_me_reconnect_attempts_total 1791
telemt_me_reconnect_success_total 1771
telemt_me_reader_eof_total 1871
telemt_me_idle_close_by_peer_total 1870
telemt_me_route_drop_no_conn_total 224948
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 100
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 911
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 585
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 268
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1875
telemt_me_writer_restored_same_endpoint_total 1768
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 440589
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 20677453452 (19.26 GB)
telemt_user_octets_to_client{user="hello"} 210510791628 (196.05 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 84
```