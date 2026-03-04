# Server Metrics 2026-03-04 10:15:38 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 47100.6 (13h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 679868
telemt_connections_bad_total 10946
telemt_handshake_timeouts_total 7518
telemt_upstream_connect_attempt_total 30956
telemt_upstream_connect_success_total 30828
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30828
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 333
telemt_me_reconnect_attempts_total 7047
telemt_me_reconnect_success_total 7003
telemt_me_reader_eof_total 7222
telemt_me_idle_close_by_peer_total 7222
telemt_me_route_drop_no_conn_total 247388
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1194
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 784
telemt_desync_frames_bucket_total{bucket="1_2"} 325
telemt_desync_frames_bucket_total{bucket="3_10"} 460
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7222
telemt_me_writer_restored_same_endpoint_total 6982
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 561070
telemt_user_connections_current{user="hello"} 1141
telemt_user_octets_from_client{user="hello"} 6275851208 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 170460346556 (158.75 GB)
telemt_user_unique_ips_current{user="hello"} 152
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 47097.0 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274231
telemt_connections_bad_total 2531
telemt_handshake_timeouts_total 26459
telemt_upstream_connect_attempt_total 94146
telemt_upstream_connect_success_total 92785
telemt_upstream_connect_fail_total 642
telemt_upstream_connect_attempts_per_request{bucket="1"} 92779
telemt_upstream_connect_attempts_per_request{bucket="2"} 648
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30479
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 642
telemt_me_keepalive_timeout_total 1348
telemt_me_reconnect_attempts_total 54322
telemt_me_reconnect_success_total 54240
telemt_me_reader_eof_total 55638
telemt_me_idle_close_by_peer_total 55637
telemt_me_route_drop_no_conn_total 124034
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 542
telemt_desync_full_logged_total 195
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 193
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55718
telemt_me_writer_restored_same_endpoint_total 54215
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 211250
telemt_user_connections_current{user="hello"} 347
telemt_user_octets_from_client{user="hello"} 2585131532 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 69657499940 (64.87 GB)
telemt_user_unique_ips_current{user="hello"} 26
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 47095.8 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548040
telemt_connections_bad_total 143389
telemt_handshake_timeouts_total 16698
telemt_upstream_connect_attempt_total 68410
telemt_upstream_connect_success_total 67987
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 67986
telemt_upstream_connect_attempts_per_request{bucket="2"} 203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39550
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28246
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 898
telemt_me_reconnect_attempts_total 31179
telemt_me_reconnect_success_total 31097
telemt_me_reader_eof_total 32782
telemt_me_idle_close_by_peer_total 32779
telemt_me_route_drop_no_conn_total 192161
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 198
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 892
telemt_desync_full_logged_total 326
telemt_desync_suppressed_total 566
telemt_desync_frames_bucket_total{bucket="1_2"} 263
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 326
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 32793
telemt_me_writer_restored_same_endpoint_total 31076
telemt_me_writer_removed_unexpected_minus_restored_total 1717
telemt_user_connections_total{user="hello"} 370733
telemt_user_connections_current{user="hello"} 617
telemt_user_octets_from_client{user="hello"} 4108046836 (3.83 GB)
telemt_user_octets_to_client{user="hello"} 130564175604 (121.60 GB)
telemt_user_unique_ips_current{user="hello"} 61
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 47094.7 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 358061
telemt_connections_bad_total 24509
telemt_handshake_timeouts_total 60358
telemt_upstream_connect_attempt_total 33797
telemt_upstream_connect_success_total 33656
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33656
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20954
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 381
telemt_me_reconnect_attempts_total 6756
telemt_me_reconnect_success_total 6733
telemt_me_reader_eof_total 6862
telemt_me_idle_close_by_peer_total 6862
telemt_me_route_drop_no_conn_total 100062
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 196
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 13
telemt_pool_force_close_total 315
telemt_me_writer_removed_unexpected_total 6862
telemt_me_writer_restored_same_endpoint_total 6712
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 250639
telemt_user_connections_current{user="hello"} 428
telemt_user_octets_from_client{user="hello"} 2719098516 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 88689506560 (82.60 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 47093.6 (13h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487078
telemt_connections_bad_total 6737
telemt_handshake_timeouts_total 132188
telemt_upstream_connect_attempt_total 68727
telemt_upstream_connect_success_total 68280
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 68280
telemt_upstream_connect_attempts_per_request{bucket="2"} 211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40992
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 901
telemt_me_reconnect_attempts_total 33533
telemt_me_reconnect_success_total 33501
telemt_me_reader_eof_total 35180
telemt_me_idle_close_by_peer_total 35179
telemt_me_route_drop_no_conn_total 151212
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 493
telemt_desync_full_logged_total 158
telemt_desync_suppressed_total 335
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35192
telemt_me_writer_restored_same_endpoint_total 33476
telemt_me_writer_removed_unexpected_minus_restored_total 1716
telemt_user_connections_total{user="hello"} 327745
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 4465063080 (4.16 GB)
telemt_user_octets_to_client{user="hello"} 81907672156 (76.28 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 51
```