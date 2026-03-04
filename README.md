# Server Metrics 2026-03-04 08:02:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 39101.6 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 444094
telemt_connections_bad_total 7963
telemt_handshake_timeouts_total 6200
telemt_upstream_connect_attempt_total 24305
telemt_upstream_connect_success_total 24193
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 24193
telemt_upstream_connect_attempts_per_request{bucket="2"} 50
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 257
telemt_me_reconnect_attempts_total 4787
telemt_me_reconnect_success_total 4754
telemt_me_reader_eof_total 4865
telemt_me_idle_close_by_peer_total 4865
telemt_me_route_drop_no_conn_total 149123
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 826
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 519
telemt_desync_frames_bucket_total{bucket="1_2"} 239
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 9
telemt_pool_force_close_total 347
telemt_me_writer_removed_unexpected_total 4865
telemt_me_writer_restored_same_endpoint_total 4733
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 372056
telemt_user_connections_current{user="hello"} 886
telemt_user_octets_from_client{user="hello"} 4340273448 (4.04 GB)
telemt_user_octets_to_client{user="hello"} 110734155708 (103.13 GB)
telemt_user_unique_ips_current{user="hello"} 89
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 39098.2 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185789
telemt_connections_bad_total 1641
telemt_handshake_timeouts_total 23651
telemt_upstream_connect_attempt_total 79651
telemt_upstream_connect_success_total 78487
telemt_upstream_connect_fail_total 544
telemt_upstream_connect_attempts_per_request{bucket="1"} 78481
telemt_upstream_connect_attempts_per_request{bucket="2"} 550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25266
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 544
telemt_me_keepalive_timeout_total 1210
telemt_me_reconnect_attempts_total 46184
telemt_me_reconnect_success_total 46107
telemt_me_reader_eof_total 47229
telemt_me_idle_close_by_peer_total 47228
telemt_me_route_drop_no_conn_total 75195
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 169
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 372
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 239
telemt_desync_frames_bucket_total{bucket="1_2"} 83
telemt_desync_frames_bucket_total{bucket="3_10"} 184
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 2
telemt_pool_force_close_total 138
telemt_pool_stale_pick_total 55
telemt_me_writer_removed_unexpected_total 47309
telemt_me_writer_restored_same_endpoint_total 46082
telemt_me_writer_removed_unexpected_minus_restored_total 1227
telemt_user_connections_total{user="hello"} 133252
telemt_user_connections_current{user="hello"} 406
telemt_user_octets_from_client{user="hello"} 1636379984 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 52068212528 (48.49 GB)
telemt_user_unique_ips_current{user="hello"} 44
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 39097.0 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 372768
telemt_connections_bad_total 109946
telemt_handshake_timeouts_total 10901
telemt_upstream_connect_attempt_total 59838
telemt_upstream_connect_success_total 59492
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 59491
telemt_upstream_connect_attempts_per_request{bucket="2"} 165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 165
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_timeout_total 795
telemt_me_reconnect_attempts_total 27708
telemt_me_reconnect_success_total 27638
telemt_me_reader_eof_total 29183
telemt_me_idle_close_by_peer_total 29180
telemt_me_route_drop_no_conn_total 115525
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 584
telemt_desync_full_logged_total 220
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 157
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 215
telemt_pool_swap_total 4
telemt_pool_force_close_total 199
telemt_me_writer_removed_unexpected_total 29194
telemt_me_writer_restored_same_endpoint_total 27617
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 239069
telemt_user_connections_current{user="hello"} 547
telemt_user_octets_from_client{user="hello"} 2274034884 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 87528626600 (81.52 GB)
telemt_user_unique_ips_current{user="hello"} 70
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 39096.0 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211665
telemt_connections_bad_total 17288
telemt_handshake_timeouts_total 7840
telemt_upstream_connect_attempt_total 29497
telemt_upstream_connect_success_total 29372
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 29372
telemt_upstream_connect_attempts_per_request{bucket="2"} 61
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 6258
telemt_me_reconnect_success_total 6243
telemt_me_reader_eof_total 6362
telemt_me_idle_close_by_peer_total 6362
telemt_me_route_drop_no_conn_total 69184
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 167
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 97
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 82
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 11
telemt_pool_force_close_total 261
telemt_me_writer_removed_unexpected_total 6362
telemt_me_writer_restored_same_endpoint_total 6222
telemt_me_writer_removed_unexpected_minus_restored_total 140
telemt_user_connections_total{user="hello"} 167595
telemt_user_connections_current{user="hello"} 344
telemt_user_octets_from_client{user="hello"} 1732318092 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 59870187052 (55.76 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 39094.6 (10h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 359656
telemt_connections_bad_total 6429
telemt_handshake_timeouts_total 131031
telemt_upstream_connect_attempt_total 56721
telemt_upstream_connect_success_total 56327
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 56327
telemt_upstream_connect_attempts_per_request{bucket="2"} 184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33653
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22523
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 149
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 770
telemt_me_reconnect_attempts_total 26545
telemt_me_reconnect_success_total 26524
telemt_me_reader_eof_total 27916
telemt_me_idle_close_by_peer_total 27915
telemt_me_route_drop_no_conn_total 101879
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 167
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 247
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 4
telemt_pool_force_close_total 117
telemt_pool_stale_pick_total 2751
telemt_me_writer_removed_unexpected_total 27930
telemt_me_writer_restored_same_endpoint_total 26499
telemt_me_writer_removed_unexpected_minus_restored_total 1431
telemt_user_connections_total{user="hello"} 214953
telemt_user_connections_current{user="hello"} 467
telemt_user_octets_from_client{user="hello"} 2710967272 (2.52 GB)
telemt_user_octets_to_client{user="hello"} 53266820592 (49.61 GB)
telemt_user_unique_ips_current{user="hello"} 49
```