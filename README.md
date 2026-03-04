# Server Metrics 2026-03-04 10:25:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 47715.2 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 697818
telemt_connections_bad_total 10953
telemt_handshake_timeouts_total 7725
telemt_upstream_connect_attempt_total 31029
telemt_upstream_connect_success_total 30901
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 30901
telemt_upstream_connect_attempts_per_request{bucket="2"} 54
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13780
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 335
telemt_me_reconnect_attempts_total 7048
telemt_me_reconnect_success_total 7004
telemt_me_reader_eof_total 7223
telemt_me_idle_close_by_peer_total 7223
telemt_me_route_drop_no_conn_total 264602
telemt_me_route_drop_channel_closed_total 2
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_single_endpoint_shadow_rotate_total 187
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1227
telemt_desync_full_logged_total 423
telemt_desync_suppressed_total 804
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 472
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 11
telemt_pool_force_close_total 451
telemt_me_writer_removed_unexpected_total 7223
telemt_me_writer_restored_same_endpoint_total 6983
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 578302
telemt_user_connections_current{user="hello"} 1046
telemt_user_octets_from_client{user="hello"} 6408286552 (5.97 GB)
telemt_user_octets_to_client{user="hello"} 175920900848 (163.84 GB)
telemt_user_unique_ips_current{user="hello"} 121
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 47711.6 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280437
telemt_connections_bad_total 2578
telemt_handshake_timeouts_total 26687
telemt_upstream_connect_attempt_total 94456
telemt_upstream_connect_success_total 93092
telemt_upstream_connect_fail_total 644
telemt_upstream_connect_attempts_per_request{bucket="1"} 93086
telemt_upstream_connect_attempts_per_request{bucket="2"} 650
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 644
telemt_me_keepalive_timeout_total 1350
telemt_me_reconnect_attempts_total 54343
telemt_me_reconnect_success_total 54261
telemt_me_reader_eof_total 55659
telemt_me_idle_close_by_peer_total 55658
telemt_me_route_drop_no_conn_total 126339
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 201
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 558
telemt_desync_full_logged_total 200
telemt_desync_suppressed_total 358
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 247
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 3
telemt_pool_force_close_total 216
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 55739
telemt_me_writer_restored_same_endpoint_total 54236
telemt_me_writer_removed_unexpected_minus_restored_total 1503
telemt_user_connections_total{user="hello"} 217011
telemt_user_connections_current{user="hello"} 450
telemt_user_octets_from_client{user="hello"} 2621424872 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 71900937300 (66.96 GB)
telemt_user_unique_ips_current{user="hello"} 43
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 47710.4 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559883
telemt_connections_bad_total 144958
telemt_handshake_timeouts_total 16969
telemt_upstream_connect_attempt_total 69718
telemt_upstream_connect_success_total 69295
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 69294
telemt_upstream_connect_attempts_per_request{bucket="2"} 203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 918
telemt_me_reconnect_attempts_total 31952
telemt_me_reconnect_success_total 31869
telemt_me_reader_eof_total 33592
telemt_me_idle_close_by_peer_total 33588
telemt_me_route_drop_no_conn_total 199470
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 920
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 275
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 4
telemt_pool_force_close_total 201
telemt_me_writer_removed_unexpected_total 33603
telemt_me_writer_restored_same_endpoint_total 31848
telemt_me_writer_removed_unexpected_minus_restored_total 1755
telemt_user_connections_total{user="hello"} 380182
telemt_user_connections_current{user="hello"} 552
telemt_user_octets_from_client{user="hello"} 4459979732 (4.15 GB)
telemt_user_octets_to_client{user="hello"} 132700288524 (123.59 GB)
telemt_user_unique_ips_current{user="hello"} 60
```

## server4

```
telemt 3.1.6

telemt_uptime_seconds 47709.4 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368887
telemt_connections_bad_total 25061
telemt_handshake_timeouts_total 65810
telemt_upstream_connect_attempt_total 34216
telemt_upstream_connect_success_total 34075
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 34075
telemt_upstream_connect_attempts_per_request{bucket="2"} 69
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12878
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 383
telemt_me_reconnect_attempts_total 6826
telemt_me_reconnect_success_total 6802
telemt_me_reader_eof_total 6931
telemt_me_idle_close_by_peer_total 6931
telemt_me_route_drop_no_conn_total 102328
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 201
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 119
telemt_desync_frames_bucket_total{bucket="1_2"} 48
telemt_desync_frames_bucket_total{bucket="3_10"} 93
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 13
telemt_pool_force_close_total 316
telemt_me_writer_removed_unexpected_total 6931
telemt_me_writer_restored_same_endpoint_total 6781
telemt_me_writer_removed_unexpected_minus_restored_total 150
telemt_user_connections_total{user="hello"} 256426
telemt_user_connections_current{user="hello"} 386
telemt_user_octets_from_client{user="hello"} 2777220424 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 92927298564 (86.55 GB)
telemt_user_unique_ips_current{user="hello"} 34
```

## server5

```
telemt 3.1.6

telemt_uptime_seconds 47708.2 (13h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 496151
telemt_connections_bad_total 6772
telemt_handshake_timeouts_total 132253
telemt_upstream_connect_attempt_total 69055
telemt_upstream_connect_success_total 68608
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 68608
telemt_upstream_connect_attempts_per_request{bucket="2"} 211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_keepalive_timeout_total 906
telemt_me_reconnect_attempts_total 33596
telemt_me_reconnect_success_total 33564
telemt_me_reader_eof_total 35244
telemt_me_idle_close_by_peer_total 35243
telemt_me_route_drop_no_conn_total 154878
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_single_endpoint_shadow_rotate_total 199
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 518
telemt_desync_full_logged_total 169
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 176
telemt_pool_swap_total 6
telemt_pool_force_close_total 262
telemt_pool_stale_pick_total 2870
telemt_me_writer_removed_unexpected_total 35256
telemt_me_writer_restored_same_endpoint_total 33539
telemt_me_writer_removed_unexpected_minus_restored_total 1717
telemt_user_connections_total{user="hello"} 336325
telemt_user_connections_current{user="hello"} 575
telemt_user_octets_from_client{user="hello"} 4529516176 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 85569734116 (79.69 GB)
telemt_user_connections_total{user="hello2"} 1
telemt_user_octets_from_client{user="hello2"} 140 (140 B)
telemt_user_octets_to_client{user="hello2"} 104 (104 B)
telemt_user_unique_ips_current{user="hello"} 46
```