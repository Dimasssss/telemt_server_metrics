# Server Metrics 2026-03-13 21:07:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## server1

```
telemt 3.3.15

telemt_uptime_seconds 140929.7 (39h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4455561
telemt_connections_bad_total 37963
telemt_handshake_timeouts_total 106354
telemt_upstream_connect_attempt_total 29450
telemt_upstream_connect_success_total 29248
telemt_upstream_connect_fail_total 202
telemt_upstream_connect_attempts_per_request{bucket="1"} 29450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16084
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13022
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 202
telemt_me_keepalive_timeout_total 6613
telemt_me_reconnect_attempts_total 30002
telemt_me_reconnect_success_total 19884
telemt_me_reader_eof_total 21329
telemt_me_idle_close_by_peer_total 21328
telemt_me_route_drop_no_conn_total 1679314
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4080969
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 16246
telemt_desync_full_logged_total 4334
telemt_desync_suppressed_total 11912
telemt_desync_frames_bucket_total{bucket="1_2"} 4060
telemt_desync_frames_bucket_total{bucket="3_10"} 6195
telemt_desync_frames_bucket_total{bucket="gt_10"} 5991
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20484
telemt_me_refill_failed_total 312
telemt_me_writer_restored_same_endpoint_total 19871
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 259
telemt_me_writer_removed_unexpected_minus_restored_total 600
telemt_user_connections_total{user="hello"} 4083101
telemt_user_connections_current{user="hello"} 1035
telemt_user_octets_from_client{user="hello"} 60093229112 (55.97 GB)
telemt_user_octets_to_client{user="hello"} 1289905603281 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 5023
telemt_user_msgs_to_client{user="hello"} 14147
telemt_user_unique_ips_current{user="hello"} 319
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## server2

```
telemt 3.3.15

telemt_uptime_seconds 40593.5 (11h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 562473
telemt_connections_bad_total 41413
telemt_handshake_timeouts_total 12226
telemt_upstream_connect_attempt_total 11608
telemt_upstream_connect_success_total 11386
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 11608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 21
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 195
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 1894
telemt_me_reconnect_attempts_total 10722
telemt_me_reconnect_success_total 7298
telemt_me_reader_eof_total 7719
telemt_me_idle_close_by_peer_total 7718
telemt_me_route_drop_no_conn_total 207269
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488255
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1634
telemt_desync_full_logged_total 439
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 345
telemt_desync_frames_bucket_total{bucket="3_10"} 709
telemt_desync_frames_bucket_total{bucket="gt_10"} 580
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 7511
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 7290
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 600
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 490183
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 5270122161 (4.91 GB)
telemt_user_octets_to_client{user="hello"} 159927771376 (148.94 GB)
telemt_user_msgs_from_client{user="hello"} 6384
telemt_user_msgs_to_client{user="hello"} 14733
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## server3

```
telemt 3.3.15

telemt_uptime_seconds 170550.2 (47h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3242635
telemt_connections_bad_total 30311
telemt_handshake_timeouts_total 218224
telemt_upstream_connect_attempt_total 37937
telemt_upstream_connect_success_total 37916
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 37937
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 212
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_keepalive_timeout_total 10248
telemt_me_reconnect_attempts_total 34044
telemt_me_reconnect_success_total 29097
telemt_me_reader_eof_total 30876
telemt_me_idle_close_by_peer_total 30875
telemt_me_route_drop_no_conn_total 1110615
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2688048
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8881
telemt_desync_full_logged_total 2982
telemt_desync_suppressed_total 5899
telemt_desync_frames_bucket_total{bucket="1_2"} 1465
telemt_desync_frames_bucket_total{bucket="3_10"} 3233
telemt_desync_frames_bucket_total{bucket="gt_10"} 4183
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 29524
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 29056
telemt_me_writer_restored_fallback_total 41
telemt_me_async_recovery_trigger_total 368
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 2687324
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 44153830000 (41.12 GB)
telemt_user_octets_to_client{user="hello"} 948944207973 (883.77 GB)
telemt_user_msgs_from_client{user="hello"} 796
telemt_user_msgs_to_client{user="hello"} 5323
telemt_user_unique_ips_current{user="hello"} 195
telemt_user_unique_ips_recent_window{user="hello"} 82
```

## server4

```
telemt 3.3.15

telemt_uptime_seconds 170550.6 (47h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2108410
telemt_connections_bad_total 22793
telemt_handshake_timeouts_total 205107
telemt_upstream_connect_attempt_total 53047
telemt_upstream_connect_success_total 50605
telemt_upstream_connect_fail_total 2305
telemt_upstream_connect_attempts_per_request{bucket="1"} 52773
telemt_upstream_connect_attempts_per_request{bucket="2"} 137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20054
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2304
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 20221
telemt_me_reconnect_attempts_total 44098
telemt_me_reconnect_success_total 35087
telemt_me_reader_eof_total 37656
telemt_me_idle_close_by_peer_total 37649
telemt_me_route_drop_no_conn_total 743620
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1733456
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3744
telemt_desync_full_logged_total 1197
telemt_desync_suppressed_total 2547
telemt_desync_frames_bucket_total{bucket="1_2"} 993
telemt_desync_frames_bucket_total{bucket="3_10"} 1548
telemt_desync_frames_bucket_total{bucket="gt_10"} 1203
telemt_pool_swap_total 149
telemt_me_writer_removed_unexpected_total 35670
telemt_me_refill_failed_total 274
telemt_me_writer_restored_same_endpoint_total 35063
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 2494
telemt_me_writer_removed_unexpected_minus_restored_total 583
telemt_user_connections_total{user="hello"} 1739327
telemt_user_connections_current{user="hello"} 391
telemt_user_octets_from_client{user="hello"} 26967211819 (25.12 GB)
telemt_user_octets_to_client{user="hello"} 652006080806 (607.23 GB)
telemt_user_msgs_from_client{user="hello"} 50957
telemt_user_msgs_to_client{user="hello"} 129867
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 60
```

## server5

```
telemt 3.3.15

telemt_uptime_seconds 39986.1 (11h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 600449
telemt_connections_bad_total 5821
telemt_handshake_timeouts_total 5609
telemt_upstream_connect_attempt_total 8780
telemt_upstream_connect_success_total 8493
telemt_upstream_connect_fail_total 287
telemt_upstream_connect_attempts_per_request{bucket="1"} 8780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 287
telemt_me_keepalive_timeout_total 972
telemt_me_reconnect_attempts_total 31093
telemt_me_reconnect_success_total 6473
telemt_me_reader_eof_total 7370
telemt_me_idle_close_by_peer_total 7369
telemt_me_route_drop_no_conn_total 227996
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 563545
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_endpoint_quarantine_total 3
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1483
telemt_desync_full_logged_total 460
telemt_desync_suppressed_total 1023
telemt_desync_frames_bucket_total{bucket="1_2"} 446
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 445
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 7300
telemt_me_refill_failed_total 767
telemt_me_writer_restored_same_endpoint_total 6469
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 827
telemt_user_connections_total{user="hello"} 563463
telemt_user_connections_current{user="hello"} 465
telemt_user_octets_from_client{user="hello"} 8394102216 (7.82 GB)
telemt_user_octets_to_client{user="hello"} 180158658976 (167.79 GB)
telemt_user_unique_ips_current{user="hello"} 138
telemt_user_unique_ips_recent_window{user="hello"} 62
```