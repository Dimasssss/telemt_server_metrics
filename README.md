# Server Metrics 2026-03-04 14:52:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.1.6

telemt_uptime_seconds 63702.4 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1179656
telemt_connections_bad_total 14021
telemt_handshake_timeouts_total 21721
telemt_upstream_connect_attempt_total 37504
telemt_upstream_connect_success_total 37337
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 37337
telemt_upstream_connect_attempts_per_request{bucket="2"} 65
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16723
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 42
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 430
telemt_me_reconnect_attempts_total 8178
telemt_me_reconnect_success_total 8116
telemt_me_reader_eof_total 8381
telemt_me_idle_close_by_peer_total 8380
telemt_me_route_drop_no_conn_total 435013
telemt_me_route_drop_channel_closed_total 3
telemt_me_hardswap_pending_ttl_expired_total 14
telemt_me_single_endpoint_shadow_rotate_total 248
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 2256
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1516
telemt_desync_frames_bucket_total{bucket="1_2"} 670
telemt_desync_frames_bucket_total{bucket="3_10"} 856
telemt_desync_frames_bucket_total{bucket="gt_10"} 730
telemt_pool_swap_total 17
telemt_pool_force_close_total 715
telemt_pool_stale_pick_total 76
telemt_me_writer_removed_unexpected_total 8381
telemt_me_writer_restored_same_endpoint_total 8094
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 945909
telemt_user_connections_current{user="hello"} 1081
telemt_user_octets_from_client{user="hello"} 12544619620 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 318433083924 (296.56 GB)
telemt_user_unique_ips_current{user="hello"} 119
```

## server2

```
telemt 3.1.6

telemt_uptime_seconds 63699.0 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 448391
telemt_connections_bad_total 3751
telemt_handshake_timeouts_total 30109
telemt_upstream_connect_attempt_total 114835
telemt_upstream_connect_success_total 113145
telemt_upstream_connect_fail_total 807
telemt_upstream_connect_attempts_per_request{bucket="1"} 113139
telemt_upstream_connect_attempts_per_request{bucket="2"} 813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39369
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 807
telemt_me_keepalive_timeout_total 1523
telemt_me_reconnect_attempts_total 62694
telemt_me_reconnect_success_total 62594
telemt_me_reader_eof_total 64226
telemt_me_idle_close_by_peer_total 64225
telemt_me_route_drop_no_conn_total 182331
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 267
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1026
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 717
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 422
telemt_desync_frames_bucket_total{bucket="gt_10"} 409
telemt_pool_swap_total 4
telemt_pool_force_close_total 281
telemt_pool_stale_pick_total 56
telemt_me_writer_removed_unexpected_total 64306
telemt_me_writer_restored_same_endpoint_total 62569
telemt_me_writer_removed_unexpected_minus_restored_total 1737
telemt_user_connections_total{user="hello"} 351674
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 5633845984 (5.25 GB)
telemt_user_octets_to_client{user="hello"} 112684810320 (104.95 GB)
telemt_user_unique_ips_current{user="hello"} 47
```

## server3

```
telemt 3.1.6

telemt_uptime_seconds 63697.7 (17h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901556
telemt_connections_bad_total 189059
telemt_handshake_timeouts_total 29695
telemt_upstream_connect_attempt_total 84919
telemt_upstream_connect_success_total 84363
telemt_upstream_connect_fail_total 268
telemt_upstream_connect_attempts_per_request{bucket="1"} 84362
telemt_upstream_connect_attempts_per_request{bucket="2"} 269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34263
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 268
telemt_me_keepalive_timeout_total 1104
telemt_me_reconnect_attempts_total 38139
telemt_me_reconnect_success_total 38040
telemt_me_reader_eof_total 40039
telemt_me_idle_close_by_peer_total 40035
telemt_me_route_drop_no_conn_total 327463
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_single_endpoint_shadow_rotate_total 263
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 1896
telemt_desync_full_logged_total 628
telemt_desync_suppressed_total 1268
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 696
telemt_pool_swap_total 7
telemt_pool_force_close_total 381
telemt_me_writer_removed_unexpected_total 40051
telemt_me_writer_restored_same_endpoint_total 38018
telemt_me_writer_removed_unexpected_minus_restored_total 2033
telemt_user_connections_total{user="hello"} 638607
telemt_user_connections_current{user="hello"} 823
telemt_user_octets_from_client{user="hello"} 12939819896 (12.05 GB)
telemt_user_octets_to_client{user="hello"} 216847077512 (201.95 GB)
telemt_user_unique_ips_current{user="hello"} 69
```

## server4

```
telemt 3.2.1

telemt_uptime_seconds 10375.0 (2h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153073
telemt_connections_bad_total 14290
telemt_handshake_timeouts_total 5036
telemt_upstream_connect_attempt_total 4772
telemt_upstream_connect_success_total 4772
telemt_upstream_connect_attempts_per_request{bucket="1"} 4772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1850
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 851
telemt_me_reconnect_success_total 863
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 50708
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 188
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 116
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_swap_total 3
telemt_pool_force_close_total 110
telemt_me_writer_removed_unexpected_total 870
telemt_me_writer_restored_same_endpoint_total 842
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 129040
telemt_user_connections_current{user="hello"} 522
telemt_user_octets_from_client{user="hello"} 1734440860 (1.62 GB)
telemt_user_octets_to_client{user="hello"} 60439674240 (56.29 GB)
telemt_user_unique_ips_current{user="hello"} 49
```

## server5

```
telemt 3.2.1

telemt_uptime_seconds 10734.4 (2h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 184354
telemt_connections_bad_total 1857
telemt_handshake_timeouts_total 2991
telemt_upstream_connect_attempt_total 5903
telemt_upstream_connect_success_total 5874
telemt_upstream_connect_fail_total 14
telemt_upstream_connect_attempts_per_request{bucket="1"} 5874
telemt_upstream_connect_attempts_per_request{bucket="2"} 14
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3415
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2450
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 84
telemt_me_reconnect_attempts_total 1223
telemt_me_reconnect_success_total 1232
telemt_me_reader_eof_total 1257
telemt_me_idle_close_by_peer_total 1257
telemt_me_route_drop_no_conn_total 66441
telemt_me_route_drop_channel_closed_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_floor_mode{mode="adaptive"} 1
telemt_desync_total 460
telemt_desync_full_logged_total 174
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 61
telemt_desync_frames_bucket_total{bucket="3_10"} 197
telemt_desync_frames_bucket_total{bucket="gt_10"} 202
telemt_pool_swap_total 2
telemt_pool_force_close_total 101
telemt_me_writer_removed_unexpected_total 1257
telemt_me_writer_restored_same_endpoint_total 1212
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 159595
telemt_user_connections_current{user="hello"} 590
telemt_user_octets_from_client{user="hello"} 2588848764 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 43662633648 (40.66 GB)
telemt_user_unique_ips_current{user="hello"} 57
```