# Server Metrics 2026-03-06 17:54:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.4

telemt_uptime_seconds 27125.1 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 803418
telemt_connections_bad_total 13453
telemt_handshake_timeouts_total 3431
telemt_upstream_connect_attempt_total 13549
telemt_upstream_connect_success_total 13464
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 13499
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6076
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 47
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 177
telemt_me_reconnect_attempts_total 2667
telemt_me_reconnect_success_total 2646
telemt_me_reader_eof_total 2773
telemt_me_idle_close_by_peer_total 2773
telemt_me_route_drop_no_conn_total 336447
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 108
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 4057
telemt_desync_full_logged_total 1001
telemt_desync_suppressed_total 3056
telemt_desync_frames_bucket_total{bucket="1_2"} 965
telemt_desync_frames_bucket_total{bucket="3_10"} 1437
telemt_desync_frames_bucket_total{bucket="gt_10"} 1655
telemt_pool_swap_total 5
telemt_pool_force_close_total 313
telemt_me_writer_removed_unexpected_total 2776
telemt_me_writer_restored_same_endpoint_total 2640
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 689411
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 14101453004 (13.13 GB)
telemt_user_octets_to_client{user="hello"} 255819944208 (238.25 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## server2

```
telemt 3.3.4

telemt_uptime_seconds 27125.0 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297993
telemt_connections_bad_total 1137
telemt_handshake_timeouts_total 8601
telemt_upstream_connect_attempt_total 12183
telemt_upstream_connect_success_total 12150
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 12183
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 161
telemt_me_reconnect_attempts_total 984
telemt_me_reconnect_success_total 959
telemt_me_reader_eof_total 1012
telemt_me_idle_close_by_peer_total 1012
telemt_me_route_drop_no_conn_total 159030
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_single_endpoint_shadow_rotate_total 111
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 970
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 663
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 7
telemt_pool_force_close_total 282
telemt_me_writer_removed_unexpected_total 1013
telemt_me_writer_restored_same_endpoint_total 959
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 274647
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 3393414344 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 108747201568 (101.28 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## server3

```
telemt 3.3.4

telemt_uptime_seconds 27125.0 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 579524
telemt_connections_bad_total 5573
telemt_handshake_timeouts_total 53300
telemt_upstream_connect_attempt_total 23241
telemt_upstream_connect_success_total 23127
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 23211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 345
telemt_me_reconnect_attempts_total 7970
telemt_me_reconnect_success_total 7939
telemt_me_reader_eof_total 8436
telemt_me_idle_close_by_peer_total 8436
telemt_me_route_drop_no_conn_total 306200
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 1523
telemt_desync_full_logged_total 443
telemt_desync_suppressed_total 1080
telemt_desync_frames_bucket_total{bucket="1_2"} 343
telemt_desync_frames_bucket_total{bucket="3_10"} 565
telemt_desync_frames_bucket_total{bucket="gt_10"} 615
telemt_pool_swap_total 3
telemt_pool_force_close_total 237
telemt_pool_stale_pick_total 381
telemt_me_writer_removed_unexpected_total 8451
telemt_me_writer_restored_same_endpoint_total 7932
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 500602
telemt_user_connections_current{user="hello"} 641
telemt_user_octets_from_client{user="hello"} 7377129620 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 153772628052 (143.21 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## server4

```
telemt 3.3.4

telemt_uptime_seconds 26440.8 (7h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 567265
telemt_connections_bad_total 194472
telemt_handshake_timeouts_total 14957
telemt_upstream_connect_attempt_total 18109
telemt_upstream_connect_success_total 18107
telemt_upstream_connect_attempts_per_request{bucket="1"} 18107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7893
telemt_me_keepalive_timeout_total 259
telemt_me_reconnect_attempts_total 5141
telemt_me_reconnect_success_total 5116
telemt_me_reader_eof_total 5357
telemt_me_idle_close_by_peer_total 5357
telemt_me_route_drop_no_conn_total 182527
telemt_me_route_drop_channel_closed_total 2
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 113
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 1
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_desync_total 377
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 131
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 5
telemt_pool_force_close_total 269
telemt_me_writer_removed_unexpected_total 5363
telemt_me_writer_restored_same_endpoint_total 5115
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 247
telemt_user_connections_total{user="hello"} 319777
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 5139652060 (4.79 GB)
telemt_user_octets_to_client{user="hello"} 112719875520 (104.98 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## server5

```
telemt 3.3.4

telemt_uptime_seconds 27125.3 (7h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505937
telemt_connections_bad_total 11235
telemt_handshake_timeouts_total 5385
telemt_upstream_connect_attempt_total 11385
telemt_upstream_connect_success_total 11365
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 188
telemt_me_reconnect_attempts_total 1795
telemt_me_reconnect_success_total 1775
telemt_me_reader_eof_total 1875
telemt_me_idle_close_by_peer_total 1874
telemt_me_route_drop_no_conn_total 233153
telemt_me_route_drop_channel_closed_total 6
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_single_endpoint_shadow_rotate_total 106
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_floor_mode_switch_all_total 2
telemt_me_floor_mode_switch_total{from="static",to="adaptive"} 1
telemt_me_floor_mode_switch_total{from="adaptive",to="static"} 1
telemt_desync_total 966
telemt_desync_full_logged_total 347
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 433
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 254
telemt_pool_swap_total 8
telemt_pool_force_close_total 297
telemt_pool_stale_pick_total 293
telemt_me_writer_removed_unexpected_total 1879
telemt_me_writer_restored_same_endpoint_total 1772
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 463605
telemt_user_connections_current{user="hello"} 546
telemt_user_octets_from_client{user="hello"} 20930290376 (19.49 GB)
telemt_user_octets_to_client{user="hello"} 218239014120 (203.25 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 74
```