# Server Metrics 2026-03-12 15:25:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 34032.6 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1223397
telemt_connections_bad_total 20234
telemt_handshake_timeouts_total 12297
telemt_upstream_connect_attempt_total 6829
telemt_upstream_connect_success_total 6793
telemt_upstream_connect_fail_total 36
telemt_upstream_connect_attempts_per_request{bucket="1"} 6829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3636
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3143
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 36
telemt_me_keepalive_timeout_total 415
telemt_me_reconnect_attempts_total 8973
telemt_me_reconnect_success_total 5068
telemt_me_reader_eof_total 5390
telemt_me_idle_close_by_peer_total 5389
telemt_me_route_drop_no_conn_total 435796
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1151327
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6123
telemt_desync_full_logged_total 1528
telemt_desync_suppressed_total 4595
telemt_desync_frames_bucket_total{bucket="1_2"} 1571
telemt_desync_frames_bucket_total{bucket="3_10"} 2193
telemt_desync_frames_bucket_total{bucket="gt_10"} 2359
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5250
telemt_me_refill_failed_total 121
telemt_me_writer_restored_same_endpoint_total 5055
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 182
telemt_user_connections_total{user="hello"} 1151010
telemt_user_connections_current{user="hello"} 1625
telemt_user_octets_from_client{user="hello"} 18058136492 (16.82 GB)
telemt_user_octets_to_client{user="hello"} 335807182436 (312.74 GB)
telemt_user_unique_ips_current{user="hello"} 450
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 63653.2 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 552725
telemt_connections_bad_total 6626
telemt_handshake_timeouts_total 27288
telemt_upstream_connect_attempt_total 15315
telemt_upstream_connect_success_total 15308
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 15315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7606
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7686
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1178
telemt_me_reconnect_attempts_total 12018
telemt_me_reconnect_success_total 11950
telemt_me_reader_eof_total 12693
telemt_me_idle_close_by_peer_total 12693
telemt_me_route_drop_no_conn_total 162361
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 493118
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1889
telemt_desync_full_logged_total 595
telemt_desync_suppressed_total 1294
telemt_desync_frames_bucket_total{bucket="1_2"} 833
telemt_desync_frames_bucket_total{bucket="3_10"} 603
telemt_desync_frames_bucket_total{bucket="gt_10"} 453
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 12065
telemt_me_writer_restored_same_endpoint_total 11941
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 318
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 493616
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 7528359655 (7.01 GB)
telemt_user_octets_to_client{user="hello"} 174388457590 (162.41 GB)
telemt_user_msgs_from_client{user="hello"} 353
telemt_user_msgs_to_client{user="hello"} 423
telemt_user_unique_ips_current{user="hello"} 173
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 63653.2 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1178951
telemt_connections_bad_total 6160
telemt_handshake_timeouts_total 82168
telemt_upstream_connect_attempt_total 15340
telemt_upstream_connect_success_total 15335
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 15340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8298
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 987
telemt_me_reconnect_attempts_total 13023
telemt_me_reconnect_success_total 11800
telemt_me_reader_eof_total 12438
telemt_me_idle_close_by_peer_total 12438
telemt_me_route_drop_no_conn_total 316845
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 866384
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3619
telemt_desync_full_logged_total 1112
telemt_desync_suppressed_total 2507
telemt_desync_frames_bucket_total{bucket="1_2"} 549
telemt_desync_frames_bucket_total{bucket="3_10"} 1312
telemt_desync_frames_bucket_total{bucket="gt_10"} 1758
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 11886
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 11759
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 866573
telemt_user_connections_current{user="hello"} 982
telemt_user_octets_from_client{user="hello"} 11536405384 (10.74 GB)
telemt_user_octets_to_client{user="hello"} 272325809585 (253.62 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 160
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 63653.6 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 698609
telemt_connections_bad_total 7701
telemt_handshake_timeouts_total 57804
telemt_upstream_connect_attempt_total 16834
telemt_upstream_connect_success_total 16765
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 16834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7228
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 1368
telemt_me_reconnect_attempts_total 18826
telemt_me_reconnect_success_total 13588
telemt_me_reader_eof_total 14489
telemt_me_idle_close_by_peer_total 14489
telemt_me_route_drop_no_conn_total 237166
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 599191
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1195
telemt_desync_full_logged_total 413
telemt_desync_suppressed_total 782
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 478
telemt_desync_frames_bucket_total{bucket="gt_10"} 390
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 13855
telemt_me_refill_failed_total 162
telemt_me_writer_restored_same_endpoint_total 13567
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 108
telemt_me_writer_removed_unexpected_minus_restored_total 267
telemt_user_connections_total{user="hello"} 598678
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 7250697744 (6.75 GB)
telemt_user_octets_to_client{user="hello"} 237133649212 (220.85 GB)
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 110
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 63653.3 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 786326
telemt_connections_bad_total 7479
telemt_handshake_timeouts_total 6218
telemt_upstream_connect_attempt_total 20175
telemt_upstream_connect_success_total 19926
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 20175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10125
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9693
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 1119
telemt_me_reconnect_attempts_total 23982
telemt_me_reconnect_success_total 16745
telemt_me_reader_eof_total 17515
telemt_me_idle_close_by_peer_total 17515
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 274068
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 726316
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 31
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 4
telemt_me_adaptive_floor_cpu_cores_effective 4
telemt_me_adaptive_floor_active_cap_configured 230
telemt_me_adaptive_floor_warm_cap_configured 230
telemt_desync_total 2874
telemt_desync_full_logged_total 974
telemt_desync_suppressed_total 1900
telemt_desync_frames_bucket_total{bucket="1_2"} 814
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 1077
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 17143
telemt_me_refill_failed_total 224
telemt_me_writer_restored_same_endpoint_total 16711
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 142
telemt_me_writer_removed_unexpected_minus_restored_total 398
telemt_user_connections_total{user="hello"} 726215
telemt_user_connections_current{user="hello"} 829
telemt_user_octets_from_client{user="hello"} 8672847828 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 204160421856 (190.14 GB)
telemt_user_unique_ips_current{user="hello"} 229
telemt_user_unique_ips_recent_window{user="hello"} 118
```